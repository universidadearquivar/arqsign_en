# 🟪 Directory and access control

<details>

<summary>Is it possible to organize signed documents in secured folders on ArqSign?</summary>

To organize your documents, you can access one of the tutorials below:

* [Directory structure for customers who have not yet signed documents](../directories/documents/directory-configuration-for-clients-who-have-not-yet-signed-documents.md)
* [Directory structure for customers who have already signed documents](../directories/documents/directory-configuration-for-clients-who-have-already-signed-documents.md)

or follow the step-by-step instructions described below:

**How to Create a Directory Structure:**

1. Review user permissions, leaving only your user as the Global Administrator. This will prevent other users from accessing all folders and documents. To do this, go to the [Administration > Users](../administration/administration/users.md) menu.
2. Create the directory structure in the [Documents](../directories/documents/) menu.
3. If you already have documents in the root folder, move them to the appropriate folders in the [Documents](../directories/documents/) menu.

**How to Set Directory Access Permissions:**

1. To simplify permissions, create user groups (for example, by departments or roles) in the [Administration > User Group](../administration/administration/user-groups.md) menu, as shown in the examples below:
   * Commercial – Management (Directory Profile – Administrator)
   * Commercial – Salespeople (Directory Profile – Collaborator)
   * Commercial – Other roles with read-only access (Directory Profile – Reader)
2. Add the created groups to the root folder and enable read permissions for everyone via the [Documents > Actions](../directories/documents/#individual-actions-subdirectories) menu.
3. Adjust the permissions of each department’s folders in the [Documents](../directories/documents/) menu by selecting [Actions > Edit permissions ](../directories/documents/#individual-actions-subdirectories)for the folder.
4. Create or edit users and adjust their access permissions as needed. Click on the image to enlarge.

![](<../.gitbook/assets/image (63).png>)

**Permissions for Directories:**

Only the Global Administrator of the account has access to the directories menu, which is why it’s essential to ensure that only users without access restrictions are assigned this profile. Below are some of the actions permitted for the Global Administrator in the Directories menu:

1. **User Profile** – Defined during user creation and designates the user’s permissions on the platform. Currently, there are two options:

a) Document Sender – A user without access to the platform’s administrative features.

b) Global Administrator – A user with access to all platform features.

2. **Directory Profile** – Designates the access level of a user or group to directories. Directory profiles include Administrator, Collaborator, and Reader.

a) Administrator – Users or groups with this profile can view and download content, add, move, share, and rename documents, delete or create folders, and adjust access permissions.

b) Collaborator – Users or groups with this profile can view and download content, add, move, share, and rename documents in folders they are permitted access to.

c) Reader – Users or groups with this profile can only view and download content within the folder and documents.

[Click here](https://www.youtube.com/watch?v=FHTsOb1LLSo) to watch the explanatory video.

</details>
