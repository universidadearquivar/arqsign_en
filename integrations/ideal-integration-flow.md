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

### Triggers

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
