---
icon: arrow-progress
---

# Ideal Integration Flow

The ideal ArqSIGN integration flow should combine the use of the ArqSIGN API and ArqSIGN Webhooks.

To achieve optimal automation, it is essential to configure two Webhooks: one for monitoring and another for completion.

## Monitoring Webhook

The purpose of the monitoring webhook is to keep your system updated on key actions related to the document, as well as indicate critical moments to call other ArqSIGN APIs.

In the monitoring webhook response, it is recommended not to include any document data. Since the process is not yet completed, it is unnecessary to transmit potentially large files.

### Triggers

* A process signed by a signatory
* A process with a sending failure
* A process rejected by a signatory
* A process canceled by the sender
* A process expired

### Response

* Process data
* Signatories

## Completion Webhook

The purpose of the completion webhook is to send the signed document to your system once all signatories have signed. At this stage, the system can send either the **Base64** or the link to both the signed file and its signature record. Ideally, the webhook sends the URLs of these files to your endpoint, allowing your application to handle the download. If this is not feasible, the webhook can be configured to send the Base64.

### Return

* Process data
* Signatories
* Documents
  * Process files: Link to download the file
  * Shared document links
  * Signature record: Link to download the file

With the two Webhooks configured, you can implement the following integration flow.

## Integration Flow

_Click the images to enlarge_

<figure><img src="../.gitbook/assets/image (293).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (296).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

### Detailed Workflow

1. **Sending Documents to Signatories**

At this stage, the client must implement the call to the **POST** method responsible for sending the document to be signed on the ArqSIGN platform.

**Method:**

> * **Name:** Send Signing Process V2
> * **URL:** POST [https://api-rest.arqsign.com/api/v2/processo/enviar-documento-para-assinar](https://manual.arquivar.com/arqsign-manual-or-english/integrations/api/available-methods-in-the-api/1.-process/1.1.-post-api-v2-processo-enviar-documento-para-assinar)
> * **Documentation:** [https://developers.arqsign.com/api-details#api=api-rest-arqsign\&operation=6734bb1a4640eeaf71857525](https://developers.arqsign.com/api-details#api=api-rest-arqsign\&operation=6734bb1a4640eeaf71857525)

2. **Monitoring: Failure**

If there is any failure in delivering documents to be signed by a signatory, the ArqSIGN application will trigger the **Webhook**, which will call the client’s service (URL) as configured.

After receiving this **Webhook** response, the client can implement the call to the **PATCH** method responsible for resending the process. This method can also be used to edit the delivery method for signatories who experienced delivery failures.

**Method:**

> * **Name:** Edit and Resend the Process to Pending Signatories V2
> * **URL:** PATCH [https://api-rest.arqsign.com/api/v2/processo/{idProcesso}/reenviar-processo](api/available-methods-in-the-api/1.-process/1.3.patch-api-v2-processo-idprocesso-reenviar-processo.md)
> * **Documentation:** [https://developers.arqsign.com/api-details#api=api-rest-arqsign\&operation=6734bb1a21b37c983bbe8bbe](https://developers.arqsign.com/api-details#api=api-rest-arqsign\&operation=6734bb1a21b37c983bbe8bbe)

3. **Monitoring: Signed by a Signatory**

When a signatory signs the document, the ArqSIGN application will trigger the **Webhook**, which will call the client’s service (URL) as configured.

With the data returned by the **Webhook**, the client can update their system to keep their information synchronized.

4. **Monitoring: Refusal or Cancellation**

The process can be canceled in three ways:

* When a signatory refuses to sign the document;
* When the person responsible for sending the document cancels the process via the ArqSIGN application;
* When the client calls the **PATCH** API method `Process/Cancelar-Processo` to cancel the process.

When cancellation occurs, the **Webhook** will call the client’s endpoint as configured, providing information about whether the process was canceled or if a signatory refused to sign. If the signatory refuses to sign, the application requires them to provide a justification, which will also be sent by the **Webhook**.

At this point, the client can handle the response and decide whether to restart the process by calling the **POST** method to send a new document for signing (Step 1).

5. **Monitoring: Expiration**

When the document expires, the ArqSIGN application will trigger the **Webhook**, which will call the client’s endpoint as configured.

After receiving this **Webhook** response, the client can implement the call to the **PATCH** method responsible for resending the process. This method will update the signature token for signatories who have not yet signed the document.

**Method:**

> * **Name:** Edit and Resend the Process to Pending Signatories V2
> * **URL:** PATCH [https://api-rest.arqsign.com/api/v2/processo/{idProcesso}/reenviar-processo](https://manual.arquivar.com/arqsign-manual-or-english/integrations/api/available-methods-in-the-api/1.-process/1.3.patch-api-v2-processo-idprocesso-reenviar-processo)
> * **Documentation:** [https://developers.arqsign.com/api-details#api=api-rest-arqsign\&operation=6734bb1a21b37c983bbe8bbe](https://developers.arqsign.com/api-details#api=api-rest-arqsign\&operation=6734bb1a21b37c983bbe8bbe)

6. **Conclusion**

When the last signatory signs the document, the ArqSIGN application will trigger the **Webhook**, which will call the client’s endpoint as configured.

After receiving this **Webhook** response, the client can store the signed document and its signature record in their system.

Please note that by configuring two webhooks as per our recommendation, the signed and completed document will only be transmitted at this stage via the **Webhook of Conclusion**.
