# 🔳 Change History



<details>

<summary>2.4.0 – 13/11/2024</summary>

**An adjustment was made to the process data retrieval AP**I.

* [GET/api/v2/processo/{idProcesso}](api/available-methods-in-the-api/1.-process/1.2.get-api-v2-processo-idprocesso.md)
* This service allows clients to retrieve a process via API, including its respective process data, signatories, and documents.

**Additionally, new methods have been made available**:

* [POST/api/v1/processo/{idProcesso}/buscar-anexos-signatarios](api/available-methods-in-the-api/1.-process/1.7.post-api-v1-processo-idprocesso-buscar-anexos-signatarios.md)
* Allows retrieving signatory attachments by specifying one or more signatories for the process.

- [GET/api/v1/processo/{idArquivoProcesso}/registro-assinaturas](api/available-methods-in-the-api/1.-process/1.8.get-api-v1-processo-idarquivoprocesso-registro-assinaturas.md)
- Allows retrieving the Base64 signature log of a process file.

* [POST/api/v1/diretorio/buscar-pastas](api/available-methods-in-the-api/2.-directories/2.1.post-api-v1-diretorio-buscar-pastas.md)
* Allows retrieving folder data from the account.

- [POST/api/v1/usuarios/buscar-usuarios](api/available-methods-in-the-api/3.-users/3.1.post-api-v1-usuarios-buscar-usuarios.md)
- Allows retrieving user data from the account.

* [GET/api/v1/conta/papeis-signatarios](https://manual.arquivar.com/manual-arqsign/administracao/integracoes/api/metodos-disponiveis-na-api/4.-conta/4.1.get-api-v1-conta-papeis-signatarios)
* Allows retrieving the account's signatory roles.

- POST/api/v1/conta/buscar-consumo-itens-assinatura
- Allows retrieving the quantity of items sent (Emails, WhatsApp, SMS) used by the account during a specific period.

* GET/api/v1/conta/dados-assinatura
* Allows retrieving the data of an ArqSIGN account.

- PATCH/api/v1/confwebhook/{idConfWebHook}/alterar-status
- Allows updating the status of webhook configurations.

* POST/api/v1/confwebhook
* Allows registering a webhook configuration.

</details>
