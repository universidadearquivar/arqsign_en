# 🟪 Directory configuration for clients who have already signed documents

## Directory Structure Creation

### STEP 1 – Review of User Permissions&#x20;

The key in this step is to ensure that only users who should have access to all documents being sent for signature in the account have the Global Administrator permission.&#x20;

To do this, access the Administration screen > Users and review the user profiles associated with the account, ensuring they have the Document Sender profile (except for the account manager who should have the Global Administrator profile).

<figure><img src="../../.gitbook/assets/01 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">**Only users with the Global Administrator profile can access all folders in the directory.**</mark>
{% endhint %}

***

### STEP 2 – Creation of Sectorial Folders&#x20;

1.Identify which departments will use the ArqSign Platform for sending documents for signature. Create a folder for each department accordingly. To do this, on the Documents screen, access the root folder and click on the "Include Folder" icon.

<figure><img src="../../.gitbook/assets/02 (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

2\. Enter the department name and click Save.

<figure><img src="../../.gitbook/assets/03 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

3\. Repeat the process until you have created all the necessary folders.

<figure><img src="../../.gitbook/assets/04 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">**The Global Administrator must perform all configurations, permission adjustments, user clearance, etc., before initiating the document sending process for signatures.**</mark>
{% endhint %}

***

### STEP 3 – Moving Documents to Folders&#x20;

Access the root folder of Directories, select all the documents you want to move to a specific folder, and click on the "Move" icon.

<figure><img src="../../.gitbook/assets/05 (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

Select from the list the folder to which you want to move the selected documents and click "Move."

<figure><img src="../../.gitbook/assets/06 (6).png" alt=""><figcaption></figcaption></figure>

Repeat the process with all individual documents still in the root folder. Ideally, all documents should be stored in one of the created folders, avoiding the presence of individual documents in the root folder.

***

### STEP 4 - Creation of Groups by Departments or Roles&#x20;

Create user groups by separating them by departments, roles, or a combination of both. To do this, access the Administration screen > User Groups.

{% hint style="info" %}
<mark style="color:blue;">These groups will be used to assign permissions to folders, so the way you create them will depend on how you want to assign permissions to the folders. Our suggestion is to merge the department and the role, for example:</mark>

* <mark style="color:blue;">Commercial – Management</mark>&#x20;
* <mark style="color:blue;">Commercial – Sales Representatives</mark>&#x20;
* <mark style="color:blue;">Commercial - Other roles with read-only access</mark>&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/07 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

### STEP 5 - Insertion of Created Groups in the Root Folder&#x20;

The groups created in the previous step must be inserted into the root folder of Directories with "Reader" permission. To do this, in the root folder, click on Actions > Edit Permissions.

<figure><img src="../../.gitbook/assets/08 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

Click on the "Include" icon.&#x20;

<figure><img src="../../.gitbook/assets/09 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

Select each of the groups created in the previous step, and in the "Profile" column, assign the "Document Reader" profile to all groups. Click the "Confirm" icon to save the changes.

<figure><img src="../../.gitbook/assets/10 (4).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

### STEP 6 - Adjustment of Permissions for Sectorial Folders&#x20;

Permissions for sectorial folders must be adjusted to allow access only to individuals from the respective department, and for this, the following steps are necessary:

**1. Stop inheriting permissions from the root folder:** In the "Actions" column of the desired sectorial folder, click on "Edit Authorizations." Click on "Stop Inheriting."&#x20;

<figure><img src="../../.gitbook/assets/08 (7).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/09 (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**2. Exclude groups from other departments:** Select all other groups/departments that should not have access to the content of the selected folder and click on the "Delete" icon. Only the groups that should have access to the folder should remain.

<figure><img src="../../.gitbook/assets/10 (6).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**3. Edit the access profile for the specific department:** Adjust permissions for the remaining groups by selecting them and clicking on the "Edit" icon.&#x20;

<figure><img src="../../.gitbook/assets/11 (5).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

**4. In the "Profile" column:** Define whether the group will remain only as a "Document Reader" or if it will be an "Document and Folder Administrator" or "Document Collaborator."

* _**Document and Folder Administrator:**_ A user or group of users with this directory profile can view and download content, add, move, share, and rename documents, delete or include new folders, as well as change access permissions.
* _**Document Contributor:**_ A user or group of users with this directory profile can view and download content, add, move, share, and rename documents within the folder to which they have this profile.
* _**Document Reader:**_ A user or group of users with this directory profile can only view and download the content of the folder and documents.

{% hint style="warning" %}
<mark style="color:orange;">**This process must be repeated for all other sectorial folders and subfolders that may be created within the departmental folders.**</mark>
{% endhint %}

***

## Directory Permissions

Only the Global Administrator of the account will have access to the directory menu, which is why it is so important to ensure that only unrestricted users are assigned this profile. Below are the differences between the permissions granted to each profile:

<figure><img src="../../.gitbook/assets/Actions.png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">**All users must be associated with a permission group. Therefore, the platform should enforce users to save the document in a sector-specific folder, preventing documents from being stored in the root folder.**</mark>
{% endhint %}

***

## User Permissions Creation/Maintenance&#x20;

Once the directory structure is created and permissions are applied, maintenance on the platform consists of including or excluding users from groups to grant or revoke access to specific folders.

This maintenance can be performed either in the user's profile editing or in the editing of a specific group.

_Editing a specific group:_ Access the Administration screen > User Groups. Select the desired group and include or exclude users.

_User editing:_ Access the Administration screen > Users. Select the user you wish to edit and click "Edit." Define the groups to which the user should have access and click "Save."

***

## General Rules

<details>

<summary>Folders</summary>

1. Upon creation, every account will automatically have an associated root folder.&#x20;

<!---->

2. The root folder created automatically by the platform is named after the account and can be renamed later by its Global Administrator.&#x20;

<!---->

3. Each account is allowed only one root folder. All other folders must be created within the root folder.&#x20;

<!---->

4. Documents displayed in "Directories" are only those with a status of "Completed" and are not marked as "Deleted." In other words, if a document is in the signing process, it will not appear in the directory.&#x20;

</details>

<details>

<summary>User Profiles</summary>

1. The profile of the Global Administrator user has full access to the document directory if the account plan includes access to directory functionality.&#x20;
2. The profile of the Document Sender user will have access to folder navigation if they are part of a group with at least read permissions.&#x20;

</details>
