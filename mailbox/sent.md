# 📩 Sent

### View Process

In the _Sent_ box, all documents sent by the user to signatories are displayed, including those where the user is also a signatory.

<figure><img src="../.gitbook/assets/01 (12).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

When clicking on a document, the document view screen will open, displaying the sent document, its status, and expiration date. On the right side of the screen, signatory information is shown, including personal data, signatory role, and signature status.

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

When the process contains more than one document that is not grouped, the system lists the documents in the order defined for the process documents, allowing navigation through the documents. The currently selected document is displayed on the screen for the logged-in user.

**Logged in user view**

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**View Not Logged In User**

<figure><img src="../.gitbook/assets/image (4) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

By default, the signatory's data is displayed openly on the screen. Simply close the list and continue navigating the document.

***

## Columns on the main screen – Sent

<figure><img src="../.gitbook/assets/image (5) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Document Name Column:** This column displays the document name and the signatory's name. If there are multiple signatories, the name of the first signatory is shown along with the number of others who need to sign.

**Responsible Column:** This column shows the name and email of the person who sent the document (sender). On the Sent screen, only the name and email of the user themselves are displayed.

**Status Column:** The possible statuses for a document are: "Waiting" (no participants have signed the document yet), "In Process" (one or more participants have signed the document, but there are still pending signatures), "Completed" (all participants have signed the document), and "Cancelled" (the document sending was cancelled, and the signing process was interrupted). Hovering over the status will display information about which signatories still have pending signatures and which have completed them, along with their details. The security code sent to the recipients (if any) is also displayed.

<figure><img src="../.gitbook/assets/image (6) (1) (1).png" alt="" width="424"><figcaption></figcaption></figure>

**Size Column:** This column displays the file size of the document.

**Folder Column:** This column shows the folder within the directory where the document is stored. If the user does not have permission to access the folder, "No folder" will be displayed.

**Sent Column:** Information about the date and time the document was sent.

**Completed Column:** Information about the date and time the document signing process was completed. If it has not been completed yet, this column will remain blank.

**Actions Column:** This column displays action buttons for the document. These buttons are shown based on the user's profile. The button will always display the priority action to execute, depending on the user's profile and the document's status.

**Filter Bar:** It is possible to locate one or more documents using the available filters. The search can be done by the name or email of the sender, the name of one of the signatories, the document's status (in the Sent box, documents with the statuses "Completed", "Waiting", "In Process", and "Cancelled" will be shown), the folder where the document is stored, or the completion date of the signatures.

<figure><img src="../.gitbook/assets/05 (12).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

## Individual Actions - Sent

<figure><img src="../.gitbook/assets/image (7) (1) (1).png" alt="" width="177"><figcaption></figcaption></figure>

{% hint style="info" %}
<mark style="color:blue;">It is important to note that the "Actions" displayed on the screen depend on the "Status" of the signing process.</mark>
{% endhint %}

**Resend**

It is possible to resend documents that have not been signed by all signatories. In cases where the signing deadline has expired and not all signatories have signed, the message "Expired before completion of signatures" will be displayed. In this case, the document can only be resent to those signatories who have not yet signed.

When clicking "Resend," the sending order information will be displayed for the recipients, including the email or phone number to which the document was sent, and the security code for document access (if applicable).

<figure><img src="../.gitbook/assets/image (8) (1) (1).png" alt=""><figcaption></figcaption></figure>

In the "Edit" icon, it is possible to edit the recipient's information, as well as the settings defined for document validation in the [recipient's configuration](../top-menu/new-document.md#step-2-configure-fields).

<figure><img src="../.gitbook/assets/image (9) (1).png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="info" %}
<mark style="color:blue;">The document validation data can only be edited on this screen if it was configured previously. The "Edit" option does not allow the inclusion of validation data.</mark>
{% endhint %}

**Change Folder**&#x20;

This option will only be displayed if the user has access to the folder where the document is stored. By clicking this option, the user can change the folder in the directory where the document is stored.

<figure><img src="../.gitbook/assets/image (10) (1).png" alt="" width="563"><figcaption></figcaption></figure>

**Change Owner**

By selecting this option, the user can change the document owner. After executing this action, other document management activities will no longer be available.

{% hint style="warning" %}
<mark style="color:orange;">**Only users registered under the same account as the current owner can be selected as the new owner.**</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (11) (1).png" alt="" width="531"><figcaption></figcaption></figure>

**Download File**\
When the process contains a document or is a sharing of only one document from the process, **the system downloads** the **document and the signature record** in a .zip folder.

The zip folder is named after the process name, and the signature record file is named as "**DocumentName\_SignatureRecord**."

<figure><img src="../.gitbook/assets/image (12) (1).png" alt="" width="563"><figcaption></figcaption></figure>

When the **process contains more than one document**, the system displays a modal with the documents of the process, allowing the user to select which documents they wish to download. In the case of a sharing, only the documents that have been shared should be listed.

<figure><img src="../.gitbook/assets/image (13).png" alt="" width="563"><figcaption></figcaption></figure>

**Signature Log**&#x20;

The Signature Log displays all information about the electronic and digital signatures completed during the process, including the signatories' names, date and time of signing, location, IP address of the signing location, details of the digital certificates used, and more.

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

**Cancel**&#x20;

By selecting this option, the document is canceled, and the signature process is halted.

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

**History**

This option allows users to view information about the document and its related event history. It also enables downloading the original files from the process before the signatures were completed. This option is only available for documents with the "Completed" status.

With the **events button positioned to the right**, the process data is displayed on the screen.

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

With the **events button positioned to the left**, it is possible to view the IDs and hashes of the documents, in cases where a **process contains more than one ungrouped document**.

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

**Change Renewal**&#x20;

This option is only available if the document has a "Completed" status. By selecting this option, the user can add or modify the document's renewal date, previously set in the "Schedule renewal \_\_\_ months after signing completion" field, located in the New Document > Add Documents and Recipients > Add Documents screen. To set or adjust the number of months between renewals, edit the "Renewal Interval (Months)" field.

<figure><img src="../.gitbook/assets/image (19).png" alt="" width="500"><figcaption></figcaption></figure>

**Correct**\
This button will appear when the contact information (email or phone number) for sending the document to one or more signatories is incorrect. In this case, it is necessary to correct the incorrect information for the system to resend the document.

**Delete**\
This option is used to delete the workflow. Deleted workflows will be moved to the [Deleted](deleted.md) folder.

<figure><img src="../.gitbook/assets/image (20).png" alt="" width="364"><figcaption></figcaption></figure>

**Rename**

This option is only available if the user is both the signatory and the sender of the document.

When the process contains only one document, the system allows changing the process name.

<figure><img src="../.gitbook/assets/image (21).png" alt="" width="563"><figcaption></figcaption></figure>

When the process contains more than one document, the system allows changing both the process name and the names of the documents within the process.

<figure><img src="../.gitbook/assets/image (22).png" alt="" width="563"><figcaption></figcaption></figure>

The "**Rename process documents**" field is displayed only if the logged-in user is the sender of the process and if the process contains more than one document/file.

By default, this field is unchecked, and when checked, the system lists all the documents in the process that are available for editing.

The user has the option to move documents, changing their order. When documents are moved, the system updates the numbering in front of each document.

**Share**\
This option allows the user to create an access link to one or more documents within the process, which can be shared with people who are not participants in the signature process. This link can have a set or indefinite validity period, and the user can choose whether to allow people accessing the link to also view the attachments sent by the signatories.

When a process with multiple ungrouped documents does not have document sharing, the system opens a modal for the user to select the documents they wish to share.

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

When the process with multiple documents has document sharing enabled, the system opens a modal displaying the links that have already been shared.

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

By expanding the actions of the shared link, it is possible to **view** the sharing screen again or **delete** the sharing that was previously done.

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

When sharing the documents of the process, the user has the option to send them via email by clicking the "Send Link by Email" button.

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

Add all the email addresses that should receive the shared documentation in the indicated field.

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
<mark style="color:red;">When sharing documents from a process, it is important to note that the recipient of the share will only be able to view the documents selected for sharing, not all the documents that make up the signature process.</mark>
{% endhint %}

**Viewing Shared Documents**

When sharing only one document from a process with multiple ungrouped documents, opening the document will display only the document shared with the user.

Note that only the signatories' data will be shown in the list:

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

When multiple documents from the process are shared, the list will display, in addition to the signatories' data, the other documents from the process.

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

### Batch Actions - Sent

It is possible to select multiple documents by checking the checkbox next to the file name and selecting one of the batch action icons to perform.

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

**Move Process(es)**&#x20;

By clicking this icon, it will be possible to change the folder where the selected documents are stored. This action cannot be performed on documents with the "In Progress" status.

<figure><img src="../.gitbook/assets/image (32).png" alt="" width="533"><figcaption></figcaption></figure>

**Change Owner**&#x20;

By clicking this icon, it will be possible to change the ownership of the selected documents, meaning the document's administrative functions will be transferred to another user. This action can only be undone if the new owner returns the document's ownership to the original owner or transfers it to another user. The change of ownership in a batch process must be completed within 24 hours, and to track its progress, the user must access the [My Profile menu > Requests tab](../top-menu/my-profile.md#requests-tab).

{% hint style="warning" %}
<mark style="color:orange;">**Only users registered under the same account as the current owner can be selected as the new owner.**</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (33).png" alt="" width="552"><figcaption></figcaption></figure>

**View Document**

By clicking this icon, it will be possible to view the document or documents of the signature process. This option should be used when selecting one process at a time.

**Resend**

By clicking this icon, it will be possible to resend the selected documents to recipients who have not yet signed. This action can only be performed on documents that are not marked as "Completed."

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

**Cancel Sending**&#x20;

By clicking this icon, it will be possible to cancel the sending of the selected documents, halting the signature processes. This action can only be performed on documents that are not marked as "Completed."

<figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (36).png" alt="" width="354"><figcaption></figcaption></figure>

**Delete**&#x20;

By clicking this icon, it will be possible to delete the selected documents. This action can only be performed on documents with the status "Completed" or "Canceled."

<figure><img src="../.gitbook/assets/image (37).png" alt="" width="325"><figcaption></figcaption></figure>
