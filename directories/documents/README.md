# 📁 Documents

In the Documents menu, all completed documents from the user's account are stored, meaning they have been sent by the user or any of the members within the account and signed by all the signatories involved in the signing process. In this menu, it is possible to manage the storage of these documents.

Clicking on the menu will display the root folder of the directory, where all the documents of the account will be hosted.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

***

## Root Folder of Directories&#x20;

The root folder is automatically created when the user's account is created and is, by default, named after the account. To rename it, click on "Rename" in the "Actions" column.

<figure><img src="../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Access to the Root Folder of Directories&#x20;

Access to the root directory folder is granted to users who have been designated as global administrators in the [_Administration > Users_](../../administration/administration/users.md) menu. Access for other users with the role of document sender must be granted through a group. That is, a[ _User Group_](../../administration/administration/user-groups.md) needs to be created, and access must be granted to that group. To do so, click "Edit Permissions" in the "Actions" column.

{% hint style="info" %}
<mark style="color:blue;">**GLOBAL ADMINISTRATOR vs. DOCUMENT SENDER**</mark>

<mark style="color:blue;">A</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**global administrator**</mark><mark style="color:blue;">, in addition to having all the permissions of a directory administrator, has access to all platform functionalities, including user management. The global administrator is the one who decides who the directory administrators of the account will be. Typically, the global administrator is the account owner or users they designate to have full access.</mark>

<mark style="color:blue;">A</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**document sender**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">is a user without access to platform management features.</mark>
{% endhint %}

<figure><img src="../../.gitbook/assets/03 (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

On the "Edit Authorizations" screen, click on the "Include" icon.

<figure><img src="../../.gitbook/assets/04 (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

In the "Group" field, select the group to which access will be granted and enable read permission for all under [Documents > Actions > Edit Permissions](./#individual-actions-subdirectories).

In the "Profile" field, select the profile that designates the user's or group's access permission to Directories. The directory profiles can be:

* Documents and Folders Administrator: A user or group with this directory profile can view and download content, include, move, share, and rename documents, delete or create new folders, and change access permissions.
* Documents Collaborator: A user or group with this directory profile can view and download content, include, move, share, and rename documents in the folder they have access to.
* Documents Reader: A user or group with this directory profile can only view and download the content of the folder and documents.

<figure><img src="../../.gitbook/assets/image (3) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

***

## Subdirectories&#x20;

When clicking on the root folder, subdirectories are displayed, which are subfolders created to organize documents according to the user's needs. Documents that are not stored in any of these subdirectories may also be shown.

<figure><img src="../../.gitbook/assets/image (4) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Columns on the Main Screen - Subdirectories

**Name Column:** Name of the folder or file.

**Responsible Column:** For standalone documents, the name and email of the person responsible for sending the document will be shown. In the case of folders, this field will be blank, as a folder contains documents with different responsible parties.

**Completion Date Column:** Displays the date and time of document completion. For folders, this field will be blank, as a folder contains documents with different completion dates.

**Size Column:** Displays the size of the document. For folders, this field will be blank, as a folder contains documents of varying sizes.

<figure><img src="../../.gitbook/assets/07 (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

### Individual Actions - Subdirectories

**Edit Authorizations:** This option will only be available for document folders. The permissions of subdirectories are inherited from the root directory folder, so they cannot be edited directly. The user can only change the permission settings for the root folder or remove the inheritance of permissions from the root folder.

<figure><img src="../../.gitbook/assets/08 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**Change Owner:** This option will only be available for individual documents and if the user is the sender of the document. By clicking this option, it will be possible to assign a new owner to the document. To do this, select the new owner user and click "Change."

<figure><img src="../../.gitbook/assets/09 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**Download File:** This option will only be available for individual documents. Click this option to download the signed document.

**Share:** This option will only be available for individual documents. This option allows the user to create an access link to the document, which can be shared with people who are not participants in the signing process. The link can have a set or indefinite expiration date, and the user can decide whether to allow people accessing it to also view the attachments sent by the signers.

<figure><img src="../../.gitbook/assets/image (5) (1).png" alt="" width="563"><figcaption></figcaption></figure>

**Move:** This option will only be available for individual documents. Clicking this option will allow you to change the folder where the selected documents are stored. Select the folder to which the documents will be moved and click "Move".

<figure><img src="../../.gitbook/assets/image (6) (1).png" alt="" width="563"><figcaption></figcaption></figure>

**Rename:** This option is available for individual documents and folders. It is used to rename the document or folder.

<figure><img src="../../.gitbook/assets/image (7) (1).png" alt="" width="563"><figcaption></figcaption></figure>

### Batch Actions - Subdirectories

It is possible to select more than one document by marking the checkboxes next to the file name and perform batch actions.

**Include Folder:** Used to create new folders within the directory. Click on this icon, select the parent folder under “Include in,” and enter the folder name.

**Move Documents:** Select the documents you want to move and click the “Move Documents” icon. Then, select the folder to which the documents will be moved and click “Move.”

**Delete:** Used to delete documents from the directory. This action can only be performed by global administrators or the document owner.

**Change Owner:** This option is only available for individual documents and if the user is the document sender. By clicking this option, you can assign a new owner to the document. To do this, select the new user as the owner and click “Change.”

**Search Bar:** You can search by document or folder name using the top search bar.

<figure><img src="../../.gitbook/assets/13 (3).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>
