---
icon: rectangle-history
---

# API Change Log

## 2024

<details>

<summary>2.5.0 - 26/11/2024</summary>

The Ideal Integration Flow has been updated according to the new methods made available in update 2.4.0, released on 13/11/2024.

</details>

<details>

<summary>2.4.0 - 13/11/2024</summary>

**The API for retrieving process data has been adjusted:**

* GET/api/v2/processo/{idProcesso}
  * This service allows clients, via API, to retrieve a process with its respective process data, signatories, and process documents.

**New methods have also been made available**:

* POST/api/v1/processo/{idProcesso}/buscar-anexos-signatarios
  * Allows retrieving attachments of signatories by specifying one or more signatories within the process.
* GET/api/v1/processo/{idArquivoProcesso}/registro-assinaturas
  * Allows retrieving the base64 signature record of a process file.
* POST/api/v1/diretorio/buscar-pastas
  * Allows retrieving folder data within the account.
* POST/api/v1/usuarios/buscar-usuarios
  * Allows retrieving user data from the account.
* GET/api/v1/conta/papeis-signatarios
  * Allows retrieving the signatory roles in the account.
* POST/api/v1/conta/buscar-consumo-itens-assinatura
  * Allows retrieving the quantity of signature-related items (Submissions, WhatsApp, SMS) used within a specific period.
* GET/api/v1/conta/dados-assinatura
  * Allows retrieving the details of an ArqSIGN account.
* PATCH/api/v1/confwebhook/{idConfWebHook}/alterar-status
  * Allows changing the status of webhook configurations.
* POST/api/v1/confwebhook
  * Allows registering webhook configurations

</details>

<details>

<summary>2.3.1 - 11/11/2024</summary>

Version 1 (V1) of the following methods has been discontinued:

* POST/api/v1/processo/enviar-documento-para-assinar
* GET/api/v1/processo/{idprocesso}
* PATCH/api/v1/processo/{idProcesso}/reenviar-processo

For more details, click here.

</details>

<details>

<summary>2.3.0 - 31/10/2024</summary>

The Webhook menu has been created under Integrations. Its purpose is to enable clients to monitor the progress of document signature processes. Depending on the webhook configuration, the user will receive process execution data through events/triggers.

</details>

<details>

<summary>06/09/2024</summary>

A new route for the ArqSign API has been created.\
The route [https://api.arqsign.com/](https://api.arqsign.com/) will be discontinued on 31/10/2024, and all users must update their API calls to the new route: [https://api-rest.arqsign.com/](https://api-rest.arqsign.com/).\
The official API documentation for ArqSIGN is now available at: [https://developers.arqsign.com/](https://developers.arqsign.com/).

For more details, click here.

</details>

<details>

<summary>2.2.0 - 04/09/2024</summary>

Version two (V2) of the following method has been created:

* PATCH api/v2/processo/reenviar-processo/{idProcesso}\
  This version has been completely restructured to allow not only the simple and direct resubmission of a process but also the editing of data such as email or WhatsApp delivery type, security code delivery method, signatory name, and mandatory data required for validation or autofill, depending on the account or signature type.

</details>

<details>

<summary>2.1.0 - 05/08/2024</summary>

The API menu has been created under Integrations. Its purpose is to provide the client with the access key(s) that will be used for API request management and control.

</details>

<details>

<summary>2.0.0 - 18/07/2024</summary>

Version two (V2) of the following methods has been created:

* POST api/v2/processo/enviar-documento-para-assinar\
  Parameters gerarQrCode and obrigarLeitura have been added, along with the option to send multiple .pdf documents in the process.
* GET /api/v2/processo/{idProcesso}\
  The new version of the process retrieval service returns all documents within the specified process, which is not possible using version 1 of the service.

</details>

<details>

<summary>1.17.0 - 07/02/2024</summary>

Sign Document: The system encountered an error when attempting to sign a document sent via API. The system displayed the visual representation in an incorrect position for documents sent via API with manual positioning.

</details>

## 2023

<details>

<summary>1.15.6 – 13/12/2023</summary>

On the Integrations menu screen of the ArqSIGN Platform:

1. The Training link has been removed.
2. The term "User Manual" has been changed to "API Documentation".
3. The API Documentation link has been updated to: [https://arquivar.gitbook.io/manual-arqsign/administracao/integracoes](https://arquivar.gitbook.io/manual-arqsign/administracao/integracoes).

</details>

<details>

<summary>1.15.3 – 13/11/2023</summary>

API > Validate Email CTG: The system returned a 404 error for certain domains.

</details>

<details>

<summary>1.15.2 - 02/11/2023</summary>

E-commerce API - Purchase Credits: Adjusted the purchase credits service (/api/v1/compras/comprar-creditos) to receive fiscal data and account address.

</details>

<details>

<summary>1.14.0 - 03/10/2023</summary>

API > Send Document for Signature: The system did not disregard manual position when the automatic page parameter was provided.

</details>

<details>

<summary>1.13.5 - 19/09/2023</summary>

The system displayed the certificate password in the payload of the endpoint api/v1/certificados/validar-certificado-selecionado.

</details>

<details>

<summary>1.13.4 - 18/08/2023</summary>

ArqSign API > Process Data: The system displayed the signature rejection information for all signatories instead of only for the signatory who rejected the document.

</details>

<details>

<summary>1.13.3 - 02/08/2023</summary>

API > Notification: The application displayed the account name instead of the document name in the signature notification.

</details>

<details>

<summary>1.13.0 - 27/06/2023</summary>

Integrations: Links to the ArqSIGN API manual and training were added.

</details>

<details>

<summary>1.12.3 - 26/05/2023</summary>

API > Send Document for Signature: The system did not send the document with the automatic page definition.

</details>

<details>

<summary>1.12.2 - 25/05/2023</summary>

API: The system did not apply visual representation for recipients who required representation on an automatic page.

</details>

<details>

<summary>1.11.1 - 02/05/2023</summary>

API > Send Document for Signature:

* The system sent documents via API without visual representation for type PJ when a company name and PJ document configuration were mandatory.
* The system validated the signature position for recipients whose action was to receive a copy.
* The system generated signature marking on the automatic page for recipients receiving a copy.

</details>

<details>

<summary>1.9.8 - 04/04/2023</summary>

Corrections to API service descriptions.

</details>

<details>

<summary>1.9.7 - 30/03/2023</summary>

\[API] Send Document for Signature: The application did not validate when parameters for both automatic and manual position were sent for visual representation, returning a 200 status.

When signing a document via WhatsApp sent through the API, the system displayed incorrect information alongside the visual representation, showing the signatory's phone number in the email field.

When signing a document with an electronic signature sent via API, the system did not display the certificate information linked to the signature.

</details>

<details>

<summary>1.9.4 - 14/03/2023</summary>

Sign Document: Fixed the loop generated during signing with a Digital Certificate for a document sent via API.

</details>

<details>

<summary>1.9.3 - 23/02/2023</summary>

API > Send Document for Signature: The system did not validate the delivery method for saving the signatory's contact.

</details>

## 2022

<details>

<summary>1.8.1 – 16/11/2022</summary>

API > Send Document: The system allowed sending a document using the same email in the same signing order.

</details>

<details>

<summary>1.6.4 - 03/06/2022</summary>

Adjustment in Purchase API: When receiving purchase data from e-commerce and the country was different from Brazil, the system required "Person Type," CPF/CNPJ, and ZIP code. After the adjustment, these fields are no longer mandatory when the country is not Brazil.

</details>

<details>

<summary>1.3.0 - 04/01/2022</summary>

Additional security validations were included in the API called by e-commerce in ArqSign.

</details>
