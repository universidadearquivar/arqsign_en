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

