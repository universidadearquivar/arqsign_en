# 🟪 Requirements for using the API

1. [Access your account ](https://app.gitbook.com/o/Ai1YjbPQxIuvTaVzoZ4H/s/WoZ5sO9ix7pAjCll866S/)or create a [free test account](https://app.gitbook.com/o/Ai1YjbPQxIuvTaVzoZ4H/s/WoZ5sO9ix7pAjCll866S/) on the ArqSign Platform. Once authenticated, click on the [Integrations menu and access your API AppKey](./), user ID, and folder ID.

<figure><img src="../.gitbook/assets/image.png" alt="" width="563"><figcaption></figcaption></figure>

2. For testing, use the Postman tool and for Authorization, select the AppKey type.

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

#### **R**equirements

* Have an active account on the ArqSign platform.
* Have a valid API access key, referred to as AppKey.
* For the method POST/api/v2/processo/enviar-documento-para-assinar, the following will be required:

→ _ID of an active user account:_ to be responsible for the documents to be sent via the API.

→ _Folder ID:_ where the document to be generated should be stored in the platform.

* For the method POST/api/v2/processo/enviar-documento-para-assinar, the following will be necessary:

→ An active account with ArqSign Integration permission.

→ The account must have credits for Sends, SMS, and/or WhatsApp, as needed. If the account does not have credits, the system will return a message stating "insufficient credits for Sends, WhatsApp, or SMS."

* Have an active account on the ArqSign platform.
* Have a valid API access key, referred to as AppKey.
* For the method POST/api/v2/processo/enviar-documento-para-assinar, the following will be required:

→ ID of an active user account: to be responsible for the documents to be sent via the API.

→ Folder ID: where the document to be generated should be stored in the platform.

* For the method POST/api/v2/processo/enviar-documento-para-assinar, the following will be necessary:

→ An active account with ArqSign Integration permission.

→ The account must have credits for Sends, SMS, and/or WhatsApp, as needed. If the account does not have credits, the system will return a message stating "insufficient credits for Sends, WhatsApp, or SMS."

{% hint style="warning" %}
<mark style="color:orange;">**The**</mark> [<mark style="color:blue;">**Directories**</mark>](../directories/documents/) <mark style="color:orange;">**feature will allow the client to have multiple organizational folders within the platform.**</mark>
{% endhint %}
