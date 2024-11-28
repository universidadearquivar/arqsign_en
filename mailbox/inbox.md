# ✉️ Inbox

The Inbox lists all the documents in which the user is involved in the signing process as a signer, meaning as a signatory through the ArqSign Platform.

The signer of a signing process can also be the sender of the document, and in this case, the document will be displayed both in the Inbox and the [Sent menu](sent.md).

{% hint style="warning" %}
<mark style="color:orange;">**Documents that have expired, meaning those whose signing deadline has passed, will not be displayed in the Inbox.**</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/01 (4).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

When clicking on a document, the document's viewing screen will open, displaying the sent document, its status, and the due date. On the right side of the screen, information about the signatories will be shown, including personal details, the signatory role, and the signature status.

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

***

## Main Screen Columns – Inbox

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>

**Document Name Column:** This column displays the document name and the signatory's name. If there is more than one signatory, the name of the first signatory will be shown, along with the number of additional people who need to sign.

**Responsible Column:** This column shows the name and email of the person who sent the document (the sender).

**Status Column:** The possible statuses for a document are:"Waiting" (no participants have signed the document yet), "In process" (one or more participants have signed, but signatures are still pending), and "Completed" (all participants have signed the document). Hovering over the status reveals information about which signatories still have pending signatures, which have completed signing, and details about each signatory.

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

**Size Column:** This column displays the file size of the document.

**Folder Column:** This column shows the directory folder where the document is stored. If the user does not have access to the folder, "No folder" will be displayed.

**Sent Column:** Information about the date and time the document was sent.

**Completed Column:** Information about the date and time the document signing process was completed. If it has not yet been completed, this column will remain blank.

**Actions Column:** This column displays action buttons for the document. These buttons are shown according to the user’s profile. The primary action, based on the user's profile and document status, will always be displayed on this button.

**Filter Bar:** One or more documents can be located using the available search filters. Searches can be conducted by the name or email of the sender, the name of a signatory, the document's status (only documents with "Completed," "Waiting," or "In process" statuses will be displayed in the Inbox), the folder where the document is stored, or the date the signatures were completed.

<figure><img src="../.gitbook/assets/image (3) (1).png" alt="" width="239"><figcaption></figcaption></figure>

***

## Individual Actions - Inbox

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

**Sign**\
Available only if the document has not yet been signed by the signatory and it is their turn to sign, according to the order set by the sender, if applicable. Clicking this button directs the user to [the document signing screen.](../top-menu/document-signing.md)

**History**\
Here, the user can view the history of the signing process and its documents. Select the events button to view detailed data. On this screen, the original files from the process can also be downloaded.

With the events button positioned to the right, the process data is displayed on the screen.

<figure><img src="../.gitbook/assets/image (5) (1).png" alt=""><figcaption></figcaption></figure>

When the events button is positioned to the left, the IDs and hashes of the documents can be viewed, in cases where a **process includes more than one document that is not grouped**.

<figure><img src="../.gitbook/assets/image (6) (1).png" alt=""><figcaption></figcaption></figure>

**Change Folder**&#x20;

This option is displayed only if the user has access to the account where the document is stored. By clicking this option, the user can change the directory folder where the document is stored.

<figure><img src="../.gitbook/assets/image (7) (1).png" alt="" width="563"><figcaption></figcaption></figure>

**Change Owner**&#x20;

This option is displayed only if the user is both the signatory and the sender of the document. By clicking this option, the user can change the document's owner. After executing this action, no other document management activities can be performed.

{% hint style="warning" %}
<mark style="color:orange;">**Only users registered under the same account as the current owner can be selected as the new owner.**</mark>

<mark style="color:orange;">**A Global Administrator who is not the document’s sender may change the ownership of completed documents listed in the Directories feature or when deactivating a user who owns documents.**</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (8) (1).png" alt="" width="530"><figcaption></figcaption></figure>

**Download File**\
When a process includes a single document or involves sharing only one document from the process, **the system downloads** the **document along with the signature record** in a .zip folder.

The zip folder is named after the process, and the signature record file is named as _**DocumentName\_SignatureRecord**_.

<figure><img src="../.gitbook/assets/image (125).png" alt="" width="375"><figcaption></figcaption></figure>

When **the process includes multiple documents**, the system displays a modal with the documents in the process, allowing the user to select which documents to download. In the case of a shared process, only the shared documents will be listed for selection.

<figure><img src="../.gitbook/assets/image (9) (1).png" alt="" width="560"><figcaption></figcaption></figure>

The Signature Registration displays all information regarding the electronic and digital signatures performed during the process, such as the names of the signatories, the date and time of the signature, location, the IP address from which it was signed, details of the digital certificates used, and more.

<figure><img src="../.gitbook/assets/image (10) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (12) (1).png" alt=""><figcaption></figcaption></figure>

**Cancel**\
This option is displayed only if the user is both the signatory and the sender of the document. Clicking this option cancels the document and interrupts the signing process. This option will not be displayed if the document's status is "Completed."

**Share**\
This option allows the user to create an access link to one or more documents in the process, which can be shared with individuals who are not participants in the signing process. The link can have a set expiration date or be indefinite, and the user can choose whether to allow those who access the link to view attachments sent by the signatories.

When the process contains more than one ungrouped document and there is no document sharing, the system opens a modal for the user to select the documents they wish to share.

<figure><img src="../.gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>

When the process contains multiple documents and document sharing is enabled, the system opens a modal displaying the links that have already been shared.

<figure><img src="../.gitbook/assets/image (130).png" alt=""><figcaption></figcaption></figure>

When expanding the actions of the sharing link, it is possible to view the sharing screen again or delete the shared link.

<figure><img src="../.gitbook/assets/image (131).png" alt=""><figcaption></figcaption></figure>

When sharing the documents of the process, the user has the option to send them via email by clicking the "Send Link by Email" button.

<figure><img src="../.gitbook/assets/image (132).png" alt=""><figcaption></figcaption></figure>

Add all the email addresses that should receive the shared documentation in the designated field.

<figure><img src="../.gitbook/assets/image (13) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
<mark style="color:red;">When sharing documents from a process, it is important to note that the recipient of the shared link will only be able to view the documents selected for sharing, and not all the documents that make up the signing process.</mark>
{% endhint %}

**Viewing Shared Documents**

When sharing only one document from a process with multiple ungrouped documents, upon opening the document, only the shared document will be presented to the user.

Note that only the signatories' data will be displayed in the list:

<figure><img src="../.gitbook/assets/image (134).png" alt=""><figcaption></figcaption></figure>

When multiple documents from the process are shared, the list will display, in addition to the signatories' data, the other documents from the process.

<figure><img src="../.gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>

**Change Renewal Schedule**&#x20;

This option will be displayed only if the user is both the signatory and the sender of the document. It is used to change or add a renewal deadline for the document that was previously set in the [New Document menu > Add Documents](../top-menu/new-document.md).

<figure><img src="../.gitbook/assets/image (14) (1).png" alt="" width="512"><figcaption></figcaption></figure>

**Reject Signature**&#x20;

This option is available only if the document has not yet been signed by the signatory and it is their turn to sign according to the order established by the sender, if applicable. It is used when the signatory does not wish to sign the document for any reason. In this case, the signatory must provide a justification for the rejection and click "Reject Signature."

<figure><img src="../.gitbook/assets/image (15) (1).png" alt=""><figcaption></figcaption></figure>

**Resend**&#x20;

This option will only be displayed if the user is both the signatory and the sender of the document, and if the document is expired, meaning the signature deadline has passed before all signatories have signed. When clicking this button, the system will display the sending order information for the recipients, the email or phone number to which the document was sent, the security code for accessing the document (if applicable), and the "Edit" icon, which allows editing the recipient's information.

<figure><img src="../.gitbook/assets/image (16) (1).png" alt="" width="563"><figcaption></figcaption></figure>

**Rename**

This option will only be displayed if the user is both the signatory and the sender of the document.

When the process contains only one document, the system allows the user to change the name of the process.

<figure><img src="../.gitbook/assets/image (17) (1).png" alt="" width="560"><figcaption></figcaption></figure>

When the process contains more than one document, the system allows the user to change both the name of the process and the names of the individual documents in the process.

<figure><img src="../.gitbook/assets/image (18) (1).png" alt="" width="560"><figcaption></figcaption></figure>

The "**Rename process documents**" field is displayed only if the logged-in user is the sender of the process and the process contains more than one document/file.

By default, this field is unchecked. When checked, the system lists all the documents in the process, enabling them for editing.

The user can reorder the documents by moving them. When documents are moved, the system updates the numbering in front of each document.

**Delete:** Used to delete the file, which will then be moved to the [Deleted ](deleted.md)folder.

<figure><img src="../.gitbook/assets/image (19) (1).png" alt="" width="308"><figcaption></figcaption></figure>

***

### Batch Actions – Inbox

It is possible to select multiple documents by checking the checkboxes next to the file names and perform batch actions. Batch actions can only be executed on documents where the user is, in addition to being a signatory, the sender of the document.

<figure><img src="../.gitbook/assets/image (20) (1).png" alt=""><figcaption></figcaption></figure>

**Move Process(es)**&#x20;

Clicking this icon will allow you to change the folder where the selected documents are stored. This action can only be performed on documents where the user is, in addition to being a signatory, the sender of the document.

<figure><img src="../.gitbook/assets/image (21) (1).png" alt="" width="563"><figcaption></figcaption></figure>

**Resend**&#x20;

Clicking this icon will allow you to resend the selected documents to recipients who have not yet signed. This action can only be performed on documents where the user is, in addition to being a signatory, the sender of the document and that are not marked with the status "Completed."

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

**Cancel Send**&#x20;

Clicking this icon will allow you to cancel the sending of the selected documents, halting the signature processes. This action can only be performed on documents where the user is, in addition to being a signatory, the sender of the document and that are not marked with the status "Completed."

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

**Delete**&#x20;

Clicking this icon will allow you to delete the selected documents. This action can only be performed on documents where the user is, in addition to being a signatory, the sender of the document and that have the status "Completed."

<figure><img src="../.gitbook/assets/image (24).png" alt="" width="307"><figcaption></figcaption></figure>
