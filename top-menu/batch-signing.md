# 🖊️ Batch Signing

The batch signing process allows the user to sign multiple documents at once. Batch signing is only available to users with a registered account on the platform and who are authenticated. On this screen, up to 100 documents per page will be displayed, depending on the number of pending documents for signature.

{% hint style="warning" %}
<mark style="color:orange;">**Documents that require a security code are not listed for batch signing. To sign them, the user must access their Inbox and sign them individually.**</mark>
{% endhint %}

***

## Columns on the main screen - Batch Signing

<figure><img src="../.gitbook/assets/02 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**Column Document Name:** In this column, the document's name is displayed.&#x20;

**Responsible Column:** This column shows the name and email of the person who sent the document (sender).&#x20;

**Column Signature Type:** In this column, the required signature type for signing the document is displayed.&#x20;

**Actions Column:** This column displays action buttons for the document. The primary action button, based on the user's profile and document status, will always be displayed in this button.&#x20;

**Filter Bar:** You can locate one or more documents using the available filters for search. In the Batch Signing screen, searches can be performed by document name, responsible person's name, or the required signature type.&#x20;

<figure><img src="../.gitbook/assets/03 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

## Individual Actions – Batch Signature

<figure><img src="../.gitbook/assets/07 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**Status:** Clicking on this button displays the status of the document, which can be "Pending" (no participant has signed the document yet) or "In process" (one or more participants have already signed the document, but there are still pending signatures). In addition to the status, the following information about the signatories is shown: designated signing order, name and email/phone, and whether or not they have completed the signature.

<figure><img src="../.gitbook/assets/09 (4).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**Decline Signature:** Used when, for some reason, the signatory does not wish to sign the document. In this case, they must provide a reason for the refusal and click on "Decline Signature."

<figure><img src="../.gitbook/assets/08 (3).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

## Signing Documents in Bulk&#x20;

1\. Select from the list of pending documents those you want to sign and click on the "Bulk Signature" icon.&#x20;

<figure><img src="../.gitbook/assets/04 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

2\. The "Signature Data" screen will appear. Fill in the required information and click "Next". The symbol \* indicates that the information is mandatory.&#x20;

{% hint style="warning" %}
<mark style="color:orange;">**On this screen, all information defined as necessary for the signature of all selected documents in the list will be requested.**</mark>&#x20;
{% endhint %}

{% hint style="info" %}
<mark style="color:blue;">**EXAMPLE:**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">If a document specifies that the signature is for an individual, the screen will request the individual's CPF; if another document specifies a corporate signature, the screen will also request the CNPJ, and so on, until all requirements are fulfilled.</mark>&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/05 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

3\. The next step will be to define the Signature Style, which can be a standard, a drawing, or an image. Once selected, click "Finish".&#x20;

<figure><img src="../.gitbook/assets/06 (4).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

4\. If the use of a digital certificate is determined, and if not done yet, the user will be prompted to install the "ArqSign Digital Certificate" extension in the browser and the AppNative application - Desktop Module on their machine, necessary for the use of digital certificates. Once installed, all digital certificates installed on the machine and hosted in the ArqSign account will be displayed for the user to choose which one to use for the signature and enter the PIN code (if requested).&#x20;

5\. The signing process information and a counter of completed signatures will be displayed. This way, the user can monitor the signatures until all of them have been completed.&#x20;

{% hint style="info" %}
<mark style="color:blue;">**INFORMATION:**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">Depending on the number of documents sent in bulk, the user can let the ArqSign application work in the background and continue with their routine activities. It is not necessary to monitor the execution of the signing process until completion, but it is necessary to keep the login active.</mark>&#x20;
{% endhint %}

6\. Upon completing the batch signing, a completion message is displayed to the user. Click "Close" to finish. The list of pending documents for signature will be updated, showing only the documents that need to be resent to the signatories.&#x20;

{% hint style="warning" %}
<mark style="color:orange;">**In case of failures during the signing process for one or more selected documents in the batch, the platform will conclude the signing of the documents that follow the standard, report information about those that were signed, report the encountered failures, and keep as pending those documents for which the signing could not be completed.**</mark>&#x20;
{% endhint %}

{% hint style="info" %}
<mark style="color:blue;">**EXAMPLE:**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">Some reasons for possible failures include multiple users signing the document simultaneously, internet connection drop during the signing process, interrupted access, among others.</mark>&#x20;
{% endhint %}
