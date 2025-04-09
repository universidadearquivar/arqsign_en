# Table of contents

* [💻 Platform Overview 2.13.0](README.md)
* [❔ Frequently Asked Questions](frequently-asked-questions/README.md)
  * [🟪 ArqSign and Cloud Clinic](frequently-asked-questions/arqsign-and-cloud-clinic.md)
  * [🟪 Digital and electronic signature](frequently-asked-questions/digital-and-electronic-signature.md)
  * [🟪 Digital Certificate](frequently-asked-questions/digital-certificate.md)
  * [🟪 How to Use](frequently-asked-questions/how-to-use.md)
  * [🟪 Directory and access control](frequently-asked-questions/directory-and-access-control.md)
  * [🟪 Integration between Systems](frequently-asked-questions/integration-between-systems.md)
  * [🟪 Plans and payments](frequently-asked-questions/plans-and-payments.md)
  * [🟪 Security](frequently-asked-questions/security.md)
  * [🟪 Legal Validity](frequently-asked-questions/legal-validity.md)

## TOP MENU

* [➕ New Document](top-menu/new-document.md)
* [✍️ Document Signing](top-menu/document-signing.md)
* [🖊️ Batch Signature](top-menu/batch-signing.md)
* [⏱️ Overdue](top-menu/overdue.md)
* [🛒 Buy or Change Plan](top-menu/purchase-plan-or-change-plan.md)
* [💳 Buy Credits](top-menu/buy-credits.md)
* [👤 My Profile](top-menu/my-profile.md)

## MAILBOX

* [✉️ Inbox](mailbox/inbox.md)
* [📩 Sent](mailbox/sent.md)
* [✏️ Drafts](mailbox/drafts.md)
* [🗑️ Deleted](mailbox/deleted.md)
* [🗓️ Renewals](mailbox/renewals.md)

## DIRECTORIES

* [📁 Documents](directories/documents/README.md)
  * [🟪 Directory configuration for clients who have not yet signed documents](directories/documents/directory-configuration-for-clients-who-have-not-yet-signed-documents.md)
  * [🟪 Directory configuration for clients who have already signed documents](directories/documents/directory-configuration-for-clients-who-have-already-signed-documents.md)

## ADMINISTRATION

* [⚙️ Administration](administration/administration/README.md)
  * [🟪 Account](administration/administration/account.md)
  * [🟪 Users](administration/administration/users.md)
  * [🟪 User Groups](administration/administration/user-groups.md)

***

* [🧩 Integrations](integrations/README.md)
  * [🟪 API](integrations/api/README.md)
    * [🔳 Requirements for using the API](integrations/api/requirements-for-using-the-api.md)
    * [🔳 API Request Limits](integrations/api/api-request-limits.md)
    * [🔳 Available Methods in the API](integrations/api/available-methods-in-the-api/README.md)
      * [🗃️ 1. Process](integrations/api/available-methods-in-the-api/1.-process/README.md)
        * [✔️ 1.1. POST/api/v2/processo/enviar-documento-para-assinar](integrations/api/available-methods-in-the-api/1.-process/1.1.-post-api-v2-processo-enviar-documento-para-assinar.md)
        * [✔️ 1.2.GET/api/v2/processo/{idProcesso}](integrations/api/available-methods-in-the-api/1.-process/1.2.get-api-v2-processo-idprocesso.md)
        * [✔️ 1.3.PATCH/api/v2/processo/{idProcesso}/reenviar-processo](integrations/api/available-methods-in-the-api/1.-process/1.3.patch-api-v2-processo-idprocesso-reenviar-processo.md)
        * [✔️ 1.4. GET /api/v1/processo/{idProcesso}/status-do-processo](integrations/api/available-methods-in-the-api/1.-process/1.4.-get-api-v1-processo-idprocesso-status-do-processo.md)
        * [✔️ 1.5.GET/api/v1/processo/{idprocesso}/dados-signatarios](integrations/api/available-methods-in-the-api/1.-process/1.5.get-api-v1-processo-idprocesso-dados-signatarios.md)
        * [✔️ 1.6.PATCH/api/v1/processo/{idProcesso}/cancelar-processo](integrations/api/available-methods-in-the-api/1.-process/1.6.patch-api-v1-processo-idprocesso-cancelar-processo.md)
        * [✔️ 1.7.POST/api/v1/processo/{idProcesso}/buscar-anexos-signatarios](integrations/api/available-methods-in-the-api/1.-process/1.7.post-api-v1-processo-idprocesso-buscar-anexos-signatarios.md)
        * [✔️ 1.8.GET/api/v1/processo/{idArquivoProcesso}/registro-assinaturas](integrations/api/available-methods-in-the-api/1.-process/1.8.get-api-v1-processo-idarquivoprocesso-registro-assinaturas.md)
      * [🗃️ 2. Directories](integrations/api/available-methods-in-the-api/2.-directories/README.md)
        * [✔️ 2.1.POST/api/v1/diretorio/buscar-pastas](integrations/api/available-methods-in-the-api/2.-directories/2.1.post-api-v1-diretorio-buscar-pastas.md)
      * [🗃️ 3. Users](integrations/api/available-methods-in-the-api/3.-users/README.md)
        * [✔️ 3.1.POST/api/v1/usuarios/buscar-usuarios](integrations/api/available-methods-in-the-api/3.-users/3.1.post-api-v1-usuarios-buscar-usuarios.md)
      * [🗃️ 4. Account](integrations/api/available-methods-in-the-api/4.-account/README.md)
        * [✔️ 4.1.GET/api/v1/conta/papeis-signatarios](integrations/api/available-methods-in-the-api/4.-account/4.1.get-api-v1-conta-papeis-signatarios.md)
        * [✔️ 4.2.POST/api/v1/conta/buscar-consumo-itens-assinatura](integrations/api/available-methods-in-the-api/4.-account/4.2.post-api-v1-conta-buscar-consumo-itens-assinatura.md)
        * [✔️ 4.3.GET/api/v1/conta/dados-assinatura](integrations/api/available-methods-in-the-api/4.-account/4.3.get-api-v1-conta-dados-assinatura.md)
      * [🗃️ 5. Webhook](integrations/api/available-methods-in-the-api/5.-webhook/README.md)
        * [✔️ 5.1.PATCH/api/v1/confwebhook/{idConfWebHook}/alterar-status](integrations/api/available-methods-in-the-api/5.-webhook/5.1.patch-api-v1-confwebhook-idconfwebhook-alterar-status.md)
        * [✔️ 5.2.POST/api/v1/confwebhook](integrations/api/available-methods-in-the-api/5.-webhook/5.2.post-api-v1-confwebhook.md)
    * [🔳 ArqSign API URL](integrations/api/arqsign-api-url.md)
    * [🔳 Library for Postman Testing](integrations/api/library-for-postman-testing.md)
  * [🟪 Webhook](integrations/webhook.md)
  * [Ideal Integration Flow](integrations/ideal-integration-flow.md)
  * [API Change Log](integrations/api-change-log.md)
