# 🖊️ Batch Signature

The batch signature process allows the user to sign multiple documents at once. Batch signing is only available for users who have a registered account on the platform and are authenticated. On this screen, up to 100 documents will be displayed per page, depending on the number of documents pending signature.

{% hint style="danger" %}
<mark style="color:red;">Documents that require the settings:</mark>

<mark style="color:red;">•</mark> <mark style="color:red;"></mark><mark style="color:red;">**Security code**</mark>

<mark style="color:red;">**• Mandatory document reading**</mark>

<mark style="color:red;">**• Predefined Signature Style**</mark>

<mark style="color:red;">**• Signature data completion or validation**</mark>

<mark style="color:red;">**• Request to attach documents**</mark>

<mark style="color:red;">**They are not listed**</mark> <mark style="color:red;"></mark><mark style="color:red;">for batch subscription. To sign them, the user must access their</mark> [<mark style="color:blue;">Inbox</mark>](../mailbox/inbox.md) <mark style="color:red;">and sign them individually.</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (37) (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

## Main Screen Columns – Batch Signature

<figure><img src="../.gitbook/assets/02 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**Document Name Column:** This column displays the document's name.

**Responsible Party Column:** This column shows the name and email of the person who sent the document (sender).

**Signature Type Column:** This column displays the required signature type for signing the document, which can be either[ Electronic Signature](document-signing.md#completing-the-signature), [Digital Certificate Signature – ICP Brasil, or Other Digital Certificates.](document-signing.md#completing-the-signature)

**Actions Column:** This column provides action buttons for the document. The primary action, according to the user profile and document status, is always displayed on this button.

**Filter Bar:** Users can locate one or more documents using the available search filters. In the Batch Signature screen, the search can be performed by document name, responsible party name, or the type of signature to be used.

<figure><img src="../.gitbook/assets/image (87).png" alt=""><figcaption></figcaption></figure>

***

## Signing documents in batch

1.  In the list of pending documents, select the ones you wish to sign and click on the “Batch Signature” icon.

    <figure><img src="../.gitbook/assets/image (88).png" alt=""><figcaption></figcaption></figure>
2. The "Signature Data" screen will appear. Fill in the required information and click "Next." The \* symbol indicates mandatory information.

{% hint style="warning" %}
<mark style="color:orange;">On this screen, all information marked as required for signing all selected documents will be requested.</mark>
{% endhint %}

{% hint style="info" %}
<mark style="color:blue;">**Example:**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">If a document requires an individual’s signature, the signer’s CPF will be requested; if another document requires a corporate signature, the CNPJ will also be requested, and so on, until all required fields are completed.</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (89).png" alt="" width="470"><figcaption></figcaption></figure>

3. The next step is to define the [Signature Style](new-document.md#b.-recipients), which can be a standard style, a drawing, or an image. Once selected, click "Finish."

<figure><img src="../.gitbook/assets/image (90).png" alt="" width="460"><figcaption></figcaption></figure>

4. If the use of a digital certificate is required, you may use a certificate stored on the ArqSign Platform or one that is not stored on the platform. For signing with an unstored certificate, if not yet done, the user will be prompted to install the “ArqSign Digital Certificate” extension in the browser and the AppNative – Desktop Module application on their machine, which are necessary for using digital certificates.

Once installed, all digital certificates on the machine and hosted on the ArqSign account will be displayed, allowing the user to select the certificate they wish to use for the signature and enter the PIN code (if requested).

<details>

<summary>INSTALLATION OF NECESSARY PLUGINS FOR USING DIGITAL CERTIFICATES</summary>

If you have not done so yet, when signing a document for the first time using a digital certificate, the user will be prompted to install the plugins "ArqSign Digital Certificate" (available by clicking here) and AppNative – Desktop Module (provided during the process).

![](<../.gitbook/assets/image (91).png>)

1. When you click "Install Now," a window will open with the download link for the "ArqSign Digital Certificate" plugin.

![](<../.gitbook/assets/image (92).png>)

2. Install the extension according to the browser you are using.

![](<../.gitbook/assets/image (93).png>)![](<../.gitbook/assets/image (94).png>)

3. After completing the first installation, return to the ArqSign platform and proceed with the installation of the AppNative application by clicking on “Click here to download...”.

![](<../.gitbook/assets/image (95).png>)![](<../.gitbook/assets/image (96).png>)

4. After completing the second installation, return to the ArqSign platform. A message confirming the completion of the installations will be displayed.

![](<../.gitbook/assets/image (97).png>)

</details>

<figure><img src="../.gitbook/assets/image (74).png" alt="" width="532"><figcaption></figcaption></figure>

5. The signature process notification and the counter of completed signatures will be displayed. This way, the user can track the signatures until all of them are completed.

{% hint style="info" %}
<mark style="color:blue;">Depending on the number of documents sent in batch, the user can leave the ArqSign application running in the background and continue with their routine activities. It is not necessary to monitor the signature process until completion, but it is essential to keep the login active.</mark>
{% endhint %}

6. Once the batch signing is completed, a completion message will be displayed to the user. Click "Close" to finalize. The list of pending documents will be updated, showing only the documents that need to be resent to the signatories.

{% hint style="warning" %}
<mark style="color:orange;">**If any failures occur during the signing process of one or more documents selected in the batch, the platform will complete the signing of documents that meet the standard, report the signed ones and the failures encountered, and keep the documents that could not be signed as pending.**</mark>
{% endhint %}

{% hint style="info" %}
<mark style="color:blue;">**Example:**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">Some reasons for potential failures include multiple users signing the document at the same time, internet connection failure during signing, interrupted access, among others.</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>

***

## Individual Actions – Batch Signature&#x20;

<figure><img src="../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

**Status**

Clicking this button displays the current status of the document, which can be “Awaiting” (no participant has signed the document yet) or “In process” (one or more participants have already signed the document, but signatures are still pending). Additionally, the following information about the signers is shown: designated signing order, name, email/phone, and whether they have completed the signature or not.

<figure><img src="../.gitbook/assets/image (100).png" alt=""><figcaption></figcaption></figure>

**Refuse Signature**

Used when, for any reason, the signer does not wish to sign the document. In this case, they must provide a justification for the refusal and click on “Refuse Signature”.

<figure><img src="../.gitbook/assets/image (101).png" alt="" width="563"><figcaption></figcaption></figure>
