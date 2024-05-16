# 🖊️ Batch Signing

The batch signing process allows the user to sign multiple documents at once. Batch signing is only available to users with a registered account on the platform and who are authenticated. On this screen, up to 100 documents per page will be displayed, depending on the number of pending documents for signature.

{% hint style="warning" %}
<mark style="color:orange;">**Documents that require a security code are not listed for batch signing. To sign them, the user must access their Inbox and sign them individually.**</mark>
{% endhint %}

***

## Columns on the main screen - Batch Signing

<figure><img src="../.gitbook/assets/02 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**Column Document Name:** This column presents the names of the documents awaiting signature.

**Column Responsible:** Here, users can find the name and email address of the individual who sent the document (sender).

**Column Type of Signature :** This column showcases the required signature type for each document, ensuring clarity on the signing requirements.

**Column Actions:** Users can take relevant actions on documents via this column, with the primary action button prominently displayed based on user profile and document status.

**Filter Bar:** A filter bar is provided to facilitate efficient document retrieval. Users can employ filters to search for specific documents based on criteria such as document name, sender's name, or required signature type.

<figure><img src="../.gitbook/assets/03 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

## Individual Actions – Batch Signature

<figure><img src="../.gitbook/assets/07 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**Status:** The Status feature provides a snapshot of the document's progress, indicating whether it's "Pending" (awaiting signatures) or "In Process" (some signatures obtained, but more pending). It also offers details on signatories such as their designated signing order, name, contact information, and signature completion status.

<figure><img src="../.gitbook/assets/09 (4).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**Refuse Signing:** This option allows a signatory to refuse signing a document, requiring them to provide a reason for the refusal. Upon providing the reason, the signatory can confirm their decision by clicking "Refuse Signing."

<figure><img src="../.gitbook/assets/08 (3).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

## Signing Documents in Batch&#x20;

1\. Select from the list of pending documents those you want to sign and click on the "Batch Signature" icon.

<figure><img src="../.gitbook/assets/04 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

2\. The "Signature Data" screen will appear. Fill in the required information and click "Next". The symbol \* indicates that the information is mandatory.

{% hint style="warning" %}
<mark style="color:orange;">**On this screen, all information defined as necessary for the signature of all selected documents in the list will be requested.**</mark>
{% endhint %}

{% hint style="info" %}
<mark style="color:blue;">**EXAMPLE:**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">If a document specifies that the signature is for an individual, the screen will request the individual's CPF; if another document specifies a corporate signature, the screen will also request the CNPJ, and so on, until all requirements are fulfilled.</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/05 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

3\. The next step will be to define the visual representation, which can be a standard, a drawing, or an image. Once selected, click "Conclude".

<figure><img src="../.gitbook/assets/06 (4).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

4\. If the use of a digital certificate is determined, and if not done yet, the user will be prompted to install the "ArqSign Digital Certificate" extension in the browser and the AppNative application - Desktop Module on their machine, necessary for the use of digital certificates. Once installed, all digital certificates installed on the machine and hosted in the ArqSign account will be displayed for the user to choose which one to use for the signature and enter the PIN code (if requested).

5\. The signing process information and a counter of completed signatures will be displayed. This way, the user can monitor the signatures until all of them have been completed.

{% hint style="info" %}
<mark style="color:blue;">**INFORMATION:**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">Depending on the number of documents sent in bulk, the user can let the ArqSign application work in the background and continue with their routine activities. It is not necessary to monitor the execution of the signing process until completion, but it is necessary to keep the login active.</mark>
{% endhint %}

6\. Upon completing the batch signing, a completion message is displayed to the user. Click "Close" to finish. The list of pending documents for signature will be updated, showing only the documents that need to be resent to the signatories.

{% hint style="warning" %}
<mark style="color:orange;">**In case of failures during the signing process for one or more selected documents in the batch, the platform will conclude the signing of the documents that follow the standard, report information about those that were signed, report the encountered failures, and keep as pending those documents for which the signing could not be completed.**</mark>
{% endhint %}

{% hint style="info" %}
<mark style="color:blue;">**EXAMPLE:**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">Some reasons for possible failures include multiple users signing the document simultaneously, internet connection drop during the signing process, interrupted access, among others.</mark>
{% endhint %}
