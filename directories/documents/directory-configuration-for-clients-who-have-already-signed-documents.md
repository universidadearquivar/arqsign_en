# 🟪 Directory configuration for clients who have already signed documents

## Directory Structure Creation

### STEP 1 – Review of User Permissions&#x20;

The key in this step is to ensure that only users who are authorized to access all documents being sent for signature in the account have the Administrator Global permission.

To do this, go to the [Administration > Users](../../administration/administration/users.md) screen and review the user profiles associated with the account, ensuring that they are assigned the Document Sender profile (except for the account manager, who should have the Administrator Global profile).

<figure><img src="../../.gitbook/assets/01 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">**Only users with the Global Administrator profile will be able to access all the folders in the directory.**</mark>
{% endhint %}

***

### STEP 2 – Creation of Department Folders

1. Identify which departments will use the ArqSign Platform for sending documents for signature, and based on these departments, create a folder for each. To do this, in the [Documents](./) screen, access [the root folder](./#root-folder-of-directories) and click on the "Include Folder" icon.

<figure><img src="../../.gitbook/assets/02 (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

2\. Enter the department name and click Save.

<figure><img src="../../.gitbook/assets/03 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

3\. Repeat the process until all necessary folders are created.

<figure><img src="../../.gitbook/assets/04 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">**The Global Administrator must perform all configurations, permission adjustments, user releases, etc., before starting the document submission for signing.**</mark>
{% endhint %}

***

### STEP 3 – Moving Documents to Folders&#x20;

Access[ the root folder of Directories](./#root-folder-of-directories), select all the documents you want to move to a specific folder, and click the "Move" icon.

<figure><img src="../../.gitbook/assets/05 (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

Select the folder from the list to which you want to move the selected documents and click "Move."

<figure><img src="../../.gitbook/assets/06 (6).png" alt=""><figcaption></figcaption></figure>

Repeat the process with all the standalone documents that are still in the root folder. Ideally, all documents should be stored in one of the created folders, avoiding the retention of standalone documents in the root folder.

***

### STEP 4 - Creation of Groups by Departments or Roles&#x20;

Create user groups by separating them by sectors, functions, or a combination of both. To do this, go to the [Administration > User Groups](../../administration/administration/user-groups.md) screen.

{% hint style="info" %}
<mark style="color:blue;">These groups will be used to assign permissions to the folders, so the way you create them will depend on how you want to assign permissions to the folders. Our suggestion is to combine the sector and function, such as:</mark>

* <mark style="color:blue;">Commercial - Management</mark>
* <mark style="color:blue;">Commercial - Salespeople</mark>
* <mark style="color:blue;">Commercial - Other functions with read-only access</mark>
{% endhint %}

<figure><img src="../../.gitbook/assets/07 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

### STEP 5 - Insertion of Created Groups in the Root Folder&#x20;

The groups created in the previous step must be inserted into [the root folder of Directories](./#root-folder-of-directories) with "Reader" permission. To do this, go to the root folder and click on Actions > Edit Permissions.

<figure><img src="../../.gitbook/assets/08 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

Click on the "Include" icon.&#x20;

<figure><img src="../../.gitbook/assets/09 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

Select each of the groups created in the previous step, and in the “Profile” column, assign the “Document Reader” profile to all groups. Click on the “Confirm” icon to save the changes.

<figure><img src="../../.gitbook/assets/10 (4).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

### STEP 6 - Adjustment of Permissions for Sectorial Folders&#x20;

The permissions of the sector folders must be adjusted so that access is granted only to people from the sector. To do this, the following steps are necessary:

**1. Stop inheriting permissions from the root folder:** In the "Actions" column of the desired sector folder, click on "Edit Permissions". Then, click on "Stop Inheriting".

<figure><img src="../../.gitbook/assets/08 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/09 (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**2. Remove groups from other sectors:** Select all the other groups/sectors that should not have access to the content of the selected folder and click on the "Delete" icon. Only the groups that should have access to the folder should remain.

<figure><img src="../../.gitbook/assets/10 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**3. Edit the access profile of the relevant sector:** Adjust the permissions of the remaining groups by selecting them and clicking on the "Edit" icon.

<figure><img src="../../.gitbook/assets/11 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**4. In the "Profile" column:** Define whether the group will remain only as "Document Reader" or if it will be "Document and Folder Administrator" or "Document Collaborator."

* _**Document and Folder Administrator:**_ A user or group with this directory profile can view and download content, add, move, share, and rename documents, delete or create new folders, and change access permissions.
* _**Document Contributor:**_ A user or group with this directory profile can view and download content, add, move, share, and rename documents within the folder to which they have access.
* _**Document Reader:**_ A user or group with this directory profile can only view and download the content of the folder and documents.

<figure><img src="../../.gitbook/assets/image (177).png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">**This process must be repeated for all other sectorial folders and subfolders that may be created within the departmental folders.**</mark>
{% endhint %}

***

## Permissions for Directories

Only the Global Administrator of the account will have access to the directory menu, which is why it is crucial to ensure that only people with no access restrictions hold this profile. Below are the differences in permissions granted to each profile:

<figure><img src="../../.gitbook/assets/Actions.png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">**All users must be associated with a permission group. This way, the platform will require the user to save the document in a sector folder, preventing documents from being stored in the root folder.**</mark>
{% endhint %}

***

## Creation/Maintenance of Permissions by User

Once the directory structure is created and permissions are applied, maintenance on the platform consists of adding or removing users from groups to grant or revoke access to specific folders.

This maintenance can be done by editing the user or editing a specific group.

Editing a Specific Group: Access the screen[ Administration > User Groups](../../administration/administration/user-groups.md). Select the desired group and add or remove users.

Editing the User: Access the screen[ Administration > Users](../../administration/administration/users.md). Select the user you wish to edit and click Edit. Define the groups the user should have access to and click Save.

***

## General Rules

<details>

<summary>Folders</summary>

1. Every account, when created, will automatically have an associated root folder.&#x20;

<!---->

2. The automatically created root folder is named after the account and can be renamed later by the Global Administrator.inistrator.&#x20;

<!---->

3. Each account is allowed only one root folder. Any additional folders must be created within the root folder.

<!---->

4. The documents displayed in "Directories" are only those with the status "Completed" and not marked as "Deleted." This means that if a document is in the signing process, it will not appear in the directory.n other words, if a document is in the signing process, it will not appear in the directory.&#x20;

</details>

<details>

<summary>User Profiles</summary>

1. The Global Administrator profile has full access to the document directory, provided that the account's plan includes directory functionality.
2. The Document Sender user profile will have access to navigate the folders if they are part of a group that has at least "Read" permission.

</details>
