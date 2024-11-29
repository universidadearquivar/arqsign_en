# 🗓️ Renewals

In the Renewals menu, all documents that have been registered and sent for signing with the option "Schedule renewal \_\_\_ months after signature completion" checked in the [New Document screen > Add Documents and Recipients > Add Documents](../top-menu/new-document.md) will be displayed. Only documents with the "Completed" status can be shown in this screen.

<figure><img src="../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

***

## Main Screen Columns – Renewals&#x20;

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Column Name of Document:** This column displays the document name and the name of the signatory. If there are multiple signatories, it shows the name of the first one and the number of other people who still need to sign.

**Column Responsible:** This column shows the name and email of the person who sent the document (the sender). In the Renewals screen, the only name and email shown will be that of the user themselves.

**Column Status:** In the Renewals screen, the only status available for a document is “Completed” (all participants have signed the document). Hovering over the status will display information about the signatories. The security code sent to recipients (if any) will also be shown.

<figure><img src="../.gitbook/assets/image (2) (1) (1).png" alt="" width="287"><figcaption></figcaption></figure>

**Column Size:** This column displays the file size of the document.

**Column Folder:** This column shows the folder in the directory where the document is stored.

**Column Completed:** Information about the date and time when the document's signing process was completed.

**Column Renewal:** This column displays the date and time when the document is scheduled for renewal, according to the information entered in the “Schedule renewal \_\_\_ months after completion of signatures” field, on the screen [New Document > Add Documents and Recipients > Add Documents](../top-menu/new-document.md). It shows both documents with a future renewal date and those that have passed the renewal deadline but have not yet been renewed.

**Column Actions:** This column displays action buttons for the document. The button will always show the priority action for execution, based on the user's profile and the document's status.

**Filter Bar:** It is possible to locate one or more documents using the available search filters. In the Renewals screen, search can be done by document name, responsible person’s name, signatories' names, document status, folder where the document is hosted, or document’s deletion date.

<figure><img src="../.gitbook/assets/image (3) (1) (1).png" alt="" width="286"><figcaption></figcaption></figure>

***

## Individual Actions – Renewals

<figure><img src="../.gitbook/assets/image (4) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Renew**&#x20;

This action will be available if the document has reached the scheduled date and time for renewal as set in the "Schedule renewal \_\_\_ months after the completion of signatures" field, found in the "[New Document > Add Documents and Recipients > Add Documents](../top-menu/new-document.md)" screen. By clicking this button, the user will be directed to the "Add Documents and Recipients" screen, with recipient information pre-filled from the previous flow, so that the user can reconfigure and send the new document to the recipients.

{% hint style="warning" %}
<mark style="color:orange;">**Even after renewing the document and sending it to the recipients, the document will remain listed on the Renewals screen until all signatories have completed the signing.**</mark>
{% endhint %}

**Change Folder**&#x20;

By clicking this option, the user can change the folder in which the document is stored.

<figure><img src="../.gitbook/assets/image (5) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

**Change Renewal**&#x20;

This option will only be available if the document has not yet been renewed. By clicking this option, the user can change the renewal date by specifying the number of months for the document's renewal interval. It is also possible to delete the renewal by clicking "Delete Schedule."

<figure><img src="../.gitbook/assets/image (6) (1).png" alt="" width="515"><figcaption></figcaption></figure>

**History**

Here, you can view the history of the signature process and its documents. Select the events button to view the detailed data. In this screen, it is also possible to download the original files of the process.

When the events button is positioned to the right, we can observe the process data on the screen.

<figure><img src="../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

With the events button positioned to the left, it is possible to view the Ids and Hashes of the documents, in the case of a **process with more than one document that is not grouped.**

<figure><img src="../.gitbook/assets/image (7) (1).png" alt=""><figcaption></figcaption></figure>

**Change Owner**&#x20;

By clicking this option, the user will be able to change the document's owner. Once this action is executed, no other management activities for the document can be performed.

{% hint style="warning" %}
<mark style="color:orange;">**Only users registered under the same account as the responsible party can be selected as the new owner.**</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (8) (1).png" alt="" width="531"><figcaption></figcaption></figure>

**Download File**

When the process contains a single document or is a sharing of only one document from the process, **the system will download** the **document and the signature record** in a .zip folder.

The zip folder is named with the process name, and the signature record file is named as **DocumentName\_SignatureRecord**.

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

When the process **contains more than one document**, the system displays a modal with the documents from the process for the user to select which documents they wish to download. If it is a sharing, only the documents that were shared should be listed.

<figure><img src="../.gitbook/assets/image (9) (1).png" alt="" width="563"><figcaption></figcaption></figure>

The Signature Log displays all information about the electronic and digital signatures made during the process, such as the signatories' names, the date and time of the signature, location, IP address where it was made, details of the digital certificates used, etc.

<figure><img src="../.gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (159).png" alt=""><figcaption></figcaption></figure>

**Share**

This option allows the user to create an access link to one or more documents from the process, which can be shared with people who are not participants in the signing process. This link can have a defined or indefinite validity period, and the user can decide whether to allow those accessing the link to also view the attachments sent by the signatories.

When a process with more than one ungrouped document does not have document sharing, the system opens a modal for the user to select which documents from the process they wish to share.

<figure><img src="../.gitbook/assets/image (160).png" alt="" width="563"><figcaption></figcaption></figure>

When a process with more than one document has document sharing, the system opens a modal displaying the links that have already been shared.

<figure><img src="../.gitbook/assets/image (161).png" alt=""><figcaption></figcaption></figure>

When expanding the actions of the shared link, it is possible to **view** the sharing screen again or **delete** the sharing that was performed.

<figure><img src="../.gitbook/assets/image (162).png" alt=""><figcaption></figcaption></figure>

When sharing the process documents, the user has the option to send them via email by clicking the "Send Link via email" button.

<figure><img src="../.gitbook/assets/image (163).png" alt="" width="563"><figcaption></figcaption></figure>

Add all the emails that should receive the shared documentation in the indicated field.

<figure><img src="../.gitbook/assets/image (10) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
<mark style="color:red;">When sharing documents from a process, it is important to note that the recipient of the shared documents will only be able to view the documents selected for sharing, not all the documents that make up the signing process.</mark>
{% endhint %}

**Viewing Shared Documents**&#x20;

When sharing only one document from a process with multiple ungrouped documents, opening the document will present only the document shared with the user.

Note that only the signatories' data will be displayed in the list.

<figure><img src="../.gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>

When sharing more documents from the process, the list will display, in addition to the signatories' data, the other documents of the process:

<figure><img src="../.gitbook/assets/image (166).png" alt=""><figcaption></figcaption></figure>

**Delete:** Used to delete the file, which will be moved to the [Deleted folder](deleted.md).

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

**Rename:** This option will only be displayed if the user, in addition to being a signer, is also the sender of the document.

When the process contains only one document, the system allows the process name to be changed:

<figure><img src="../.gitbook/assets/image (12).png" alt="" width="467"><figcaption></figcaption></figure>

When the process contains more than one document, the system allows both the process name and the names of the documents within the process to be changed.

<figure><img src="../.gitbook/assets/image (13).png" alt="" width="467"><figcaption></figcaption></figure>

The "**Rename process documents**" field is displayed only if the logged-in user is the sender of the process and the process contains more than one document/file.

By default, this field is unchecked, and when checked, the system lists all documents within the process available for editing.

The user has the option to move the documents, changing their order. When documents are moved, the system updates the numbering in front of each document.

**Versioning**

This option allows the user to view all versions of a document that have been sent. When a document is renewed and completed, it is no longer displayed on the Renewals screen, but the information about its submission can still be viewed on the Document Versioning screen.

<figure><img src="../.gitbook/assets/image (14).png" alt="" width="563"><figcaption></figcaption></figure>

## Batch Actions - Renewals

It is possible to select multiple documents by checking the checkboxes next to the file names and perform batch actions.

<figure><img src="../.gitbook/assets/image (171).png" alt="" width="226"><figcaption></figcaption></figure>

**Move Process(es)**&#x20;

By clicking this icon, you will be able to change the folder where the selected documents are stored.

<figure><img src="../.gitbook/assets/image (15).png" alt="" width="563"><figcaption></figcaption></figure>

**Change Owner**&#x20;

By clicking this icon, you can change the ownership of the selected documents, meaning the document management functions will be transferred to another user. This action can only be undone if the new owner returns the document ownership to the original owner. Changing the document owner in bulk has a deadline of 24 hours to be completed, and to track progress, the user must access the "My Profile" menu > "Requests" tab.

{% hint style="warning" %}
<mark style="color:orange;">**Only users registered under the same account as the responsible user can be selected as new owners.**</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (16).png" alt="" width="531"><figcaption></figcaption></figure>

**Delete**&#x20;

By clicking this icon, you can delete the selected documents. This action can only be performed on documents with the status "Completed" or "Cancelled."

<figure><img src="../.gitbook/assets/image (17).png" alt="" width="307"><figcaption></figcaption></figure>
