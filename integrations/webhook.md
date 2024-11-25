# 🟪 Webhook

{% hint style="success" %}
<mark style="color:green;">It is a technology that enables communication between applications by automatically sending data between them via HTTP. Webhooks are triggered by specific events (triggers).</mark>

<mark style="color:green;">Webhooks are useful for: Automating processes, improving workflow, saving server resources and costs, integrating with third-party services and other external APIs.</mark>

<mark style="color:green;">Webhooks are similar to APIs, which allow communication between applications, but work differently. An API is a set of protocols and routines for building and interacting with software applications, while a webhook is a way for one application to notify another when a specific event occurs.</mark>
{% endhint %}

This menu allows the client to configure Webhooks to track the progress of their document signing processes.

<figure><img src="../.gitbook/assets/image (241).png" alt=""><figcaption></figcaption></figure>

According to the Webhook configuration made, the client receives the execution data of the signing processes through events/triggers.

{% hint style="info" %}
<mark style="color:blue;">This menu is displayed to users with an</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**Administrator Global**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">profile, with the appropriate</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**permission defined**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">on the platform and an</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**active subscription plan**</mark><mark style="color:blue;">, meaning the</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**account must have an "Active" status**</mark><mark style="color:blue;">.</mark>
{% endhint %}

Clicking on Webhook displays the GRID with the Webhook configurations of the logged-in user's account, sorted alphabetically by the "Name" column.

<figure><img src="../.gitbook/assets/image (232).png" alt=""><figcaption></figcaption></figure>

**Add:** Use this option to include a new configuration. When clicking on the "Add" icon, the application checks the account status and the number of configurations the account has.

{% hint style="warning" %}
<mark style="color:orange;">Only</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**accounts with an "Active" status**</mark> <mark style="color:orange;"></mark><mark style="color:orange;">can add a Webhook configuration,</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**limited to 25 configurations.**</mark>

<mark style="color:orange;">If the account is</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**active and has 25 webhook configurations**</mark><mark style="color:orange;">, the application will display the message:</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**"The account has reached the maximum limit of X webhook configurations."**</mark>

<mark style="color:orange;">If the</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**account is blocked**</mark><mark style="color:orange;">, the application will display the message:</mark> <mark style="color:orange;"></mark><mark style="color:orange;">**"The account is blocked. Only accounts with an active status can add a webhook configuration."**</mark>
{% endhint %}

**Delete:** Use this option to delete a configuration. The delete icon is enabled only after selecting one or more webhook configurations with an inactive **status and that are not being edited by another user.**

{% hint style="warning" %}
<mark style="color:orange;">It is not allowed to delete an inactive webhook configuration that is being edited by another user.</mark>
{% endhint %}

**Filter:** Use this option to filter specific configurations. The system allows users to filter by data contained in the GRID query results, not just on the current page.

* Name: Allows filtering by the name of the webhook.
* Status: Allows filtering by the webhook's status. The system lists the options **"Active," "Inactive," and "Inactive due to failures."**

<figure><img src="../.gitbook/assets/image (233).png" alt=""><figcaption></figcaption></figure>

**Column Id:** Displays the Webhook ID in the system.

**Column Name:** Displays the name of the Webhook in the system. When the webhook is being edited, the system signals with the message <mark style="color:red;">**"Being edited by: \[Name of the user who is editing the webhook]."**</mark>

**Column Status:** Displays the status of the webhook: **Active, Inactive, or Inactive due to failures.**

When the status is **"Active"**, it may have the following flags:

* **Trigger Inactive:** When at least one trigger in the configuration is inactive due to recurring failures.
* **Trigger Failure:** When there are no inactive triggers in the configuration, but at least one trigger has a failure count greater than zero.

**Column Actions:** This button is displayed:

* Disabled for webhook configurations with the "Being edited" flag by another user.
* Enabled for webhook configurations without the "Being edited" flag by the logged-in user.

When enabled, the system lists the actions, depending on the webhook's status: Activate, Edit, Delete, Deactivate.

* **Activate:** Only for webhook configurations with an Inactive status.
* **Edit:** Listed for all webhooks.
* **Delete:** Only for webhook configurations with an Inactive status.
* **Deactivate:** Only for webhook configurations with an Active status.

## Webhook Settings

When clicking on "Add" "+", the screen for configuring the webhook is displayed.

<figure><img src="../.gitbook/assets/image (234).png" alt=""><figcaption></figcaption></figure>

### General Data

The general data for the webhook must be provided in this area:

<figure><img src="../.gitbook/assets/image (235).png" alt=""><figcaption></figcaption></figure>

**Status:** The options "Active" and "Inactive" are displayed in the list, with "Active" being selected by default.

{% hint style="info" %}
<mark style="color:blue;">In the view/edit of an already created webhook, if its status is "Inactive due to failures," it will open with the status "Inactive."</mark>
{% endhint %}

**Name:** Enter the name of the webhook. This is a mandatory field. The system does not allow multiple webhooks with the same name in the same account.

**URL to publish:** Enter the URL that will be called to receive the data from the document signing process. This is a mandatory field.

**Wait for response:** Define whether the webhook should wait for a response. This is an optional field.

{% hint style="info" %}
<mark style="color:blue;">Checking this box will make the webhook wait for a confirmation from the listener (URL to publish) after sending a message. The webhook records a successful message transfer when the listener returns an HTTP status code 200. If this option is not checked and the webhook does not receive an HTTP status code 200, the application will not consider it a failure.</mark>
{% endhint %}

### Execute the webhook when

This section defines the prerequisites for executing the webhook.

<figure><img src="../.gitbook/assets/image (236).png" alt=""><figcaption></figcaption></figure>

**Add Groups and Users**&#x20;

This option is used to configure one or more groups and/or users as execution parameters for the webhook. In other words, the webhook will only be executed if the sender of the process is a selected user or belongs to a group configured in this field. This is an optional field.

{% hint style="danger" %}
<mark style="color:red;">If one of the listed groups is later deleted, it will be displayed in red.</mark>

<mark style="color:red;">If one of the listed users is later deactivated, blocked, or no longer an administrator, it will be displayed in red.</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (237).png" alt="" width="563"><figcaption></figcaption></figure>

On the right side of the screen, the available "Groups" and "Users" for selection are displayed. On the left side of the screen, the "Groups" and "Users" that have already been selected are shown.

<figure><img src="../.gitbook/assets/image (238).png" alt="" width="563"><figcaption></figcaption></figure>

Use the available buttons, click on the group or user name you wish to move, and then click the "Add" button to send one at a time, or "Add All" to send the entire list. The same process should be followed to "Remove" items from the list.

Once the selection of users and groups is complete, click "Select" to return to the previous screen.

<figure><img src="../.gitbook/assets/image (239).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
<mark style="color:green;">The configurations made will be displayed in the field "The process has been sent by a user from the selected group or user in this field," which is verified for "Webhook execution."</mark>
{% endhint %}

**Add Folders**&#x20;

This option is used to configure one or more folders as execution parameters for the webhook. In other words, the webhook will only be executed if the process was created in a folder contained in this field. The selected folders will be displayed in the "Folders" modal. This is an optional field.

<figure><img src="../.gitbook/assets/image (240).png" alt="" width="563"><figcaption></figcaption></figure>

Select the folder from the presented tree where you want to restrict the webhook's execution. The "Selected Folders" field will list all the marked folders. Click "Select" to complete the configuration.

{% hint style="danger" %}
<mark style="color:red;">If one of the listed folders is later deleted, it will be displayed in red.</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (242).png" alt="" width="563"><figcaption></figcaption></figure>

Carefully read the process validation message and click to proceed.

<figure><img src="../.gitbook/assets/image (243).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
<mark style="color:green;">The settings made will be displayed in the field "The process has been created in one of the folders selected in this field," which is checked for "Webhook Execution."</mark>
{% endhint %}

### Triggers

In this area, you must define one or more execution triggers for the webhook. This means specifying the moments when the webhook will be executed, calling the URL with the JSON data, according to the return configuration.

<figure><img src="../.gitbook/assets/image (244).png" alt=""><figcaption></figcaption></figure>

At least one trigger must be selected for the webhook execution. The following options are available:

1. Process Sent
2. Process Sending Failed
3. Process Signed by a Signatory
4. Process Rejected by a Signatory
5. Process Canceled by the Sender
6. Process Expired
7. Process Resent
8. Process Signed/Completed by All Signatories

### Return

In this area, you define the data that will be returned in the JSON, in addition to the general data.

<figure><img src="../.gitbook/assets/image (245).png" alt=""><figcaption></figcaption></figure>

The possible data options are:

* Process: A section of the JSON containing process data.
* Signatories: A section of the JSON containing signatory data.
* Documents: A section of the JSON containing document data for the process.

{% hint style="danger" %}
<mark style="color:red;">The general data forms the beginning of the JSON and will always be sent, even if no specific return data is marked for inclusion in the JSON.</mark>
{% endhint %}

### JSON

In this area, the system displays an example of the JSON return.

<figure><img src="../.gitbook/assets/image (246).png" alt=""><figcaption></figcaption></figure>

The configured return data is represented in the JSON field as the options are selected.

<figure><img src="../.gitbook/assets/image (247).png" alt=""><figcaption></figcaption></figure>

* When the "**Process Data**" field is selected, the system displays an example of the process data in the "JSON" field.
* When the "**Signatories**" field is selected, the system displays an example of the signatory data in the "JSON" field.
* When the "**Documents**" field is selected, the checkboxes "Process Files," "Shared Document Links," and "Signature Records" are automatically checked.

"**Process Files**" and "**Signature Records**" can be returned in either Download Link or Base64 format. It is necessary to select a format option for the process files and/or signature records.

The "**Shared Document Links**" are the links to share the documents of the process. These links are only available upon completion of processes that have the "**GenerateQRCode**" configuration. Once the settings are completed, click "Save." New tabs will be enabled for the progress of the configurations.

<figure><img src="../.gitbook/assets/image (248).png" alt=""><figcaption></figcaption></figure>

## HMAC

Every configuration made on the platform will generate an HMAC key. To view it, click on the HMAC tab.

**HMAC** is a way to verify the authenticity and integrity of the information being transmitted through a shared secret key between the parties.

For each webhook generated in ArqSIGN, the application will generate the "**HMAC Secret Key.**" This key will be known only by ArqSIGN and the client's application.

The "**HMAC Secret Key**" and the body of the request must be used to calculate the SHA256 HMAC hash. This hash will be sent in the request header as "**HMAC**."

<figure><img src="../.gitbook/assets/image (249).png" alt="" width="563"><figcaption></figcaption></figure>

Using the available icons on the screen, the user will be able to:

<figure><img src="../.gitbook/assets/image (250).png" alt="" width="563"><figcaption></figcaption></figure>

**View:** By clicking on the icon, the HMAC key will be displayed on the screen.

<figure><img src="../.gitbook/assets/image (251).png" alt="" width="563"><figcaption></figcaption></figure>

**Copy:** After clicking on the view icon, the option to "Copy" the HMAC key will be enabled.

<figure><img src="../.gitbook/assets/image (252).png" alt="" width="563"><figcaption></figcaption></figure>

**Regenerate Key:** By clicking this option, a new HMAC key will be generated by the system.

<figure><img src="../.gitbook/assets/image (253).png" alt=""><figcaption></figcaption></figure>

Please validate the action on the screen to proceed.

***

## Trigger

This section lists the configured triggers for the specific webhook, ordered by execution event.

A webhook configuration can have up to 8 triggers:

1. Process sent
2. Process failed to send
3. Process signed by a signatory
4. Process rejected by a signatory
5. Process canceled by the sender
6. Process expired
7. Process resent
8. Process signed/completed by all signatories

<figure><img src="../.gitbook/assets/image (254).png" alt=""><figcaption></figcaption></figure>

**Webhook Triggers:** Displays the name entered in the configuration screen for the process.

**Trigger Column:** Lists the triggers selected in the configuration screen.

**Failure Count Column:** The system displays the number of failures recorded for each trigger, if any.

**Status Column:** Shows the status of each trigger.

For triggers with the status "**inactive due to recurring failures**" and not being edited by another user, the system displays the "**Activate**" button, allowing the user to reactivate the trigger.

When reactivating a trigger that was inactive due to recurring failures, the system resets the failure count.

**Actions Column:** Allows reactivation of a trigger that was deactivated due to recurring failures, as long as no other user is editing that trigger.

### **Execution**

For each event in the application, as per the listed triggers, the system executes the webhook, sending updates (event messages) to the URL configured in real-time, i.e., at the moment the configured event occurs.

1. **Process Sent:** When sending a process via the ArqSign application or API, the system executes the webhook with this trigger, sending the data according to the return configuration to the configured URL.
2. **Process with Sending Failure:** When there is a failure in sending the process to a recipient and/or failure in sending the security code to a recipient.

{% hint style="danger" %}
<mark style="color:red;">Return JSON: When marked to return the "Signatories" data for this specific trigger, the response will only include the data of the signatory who experienced the failure in sending the process and/or security code.</mark>
{% endhint %}

3. **Signed process by a signatory:** As soon as the process is signed by each signatory. Therefore, if the process has 3 signatories, the webhook with this configuration will call the defined URL every time a signature is completed, meaning that by the end of the signing process, the URL will have been called 3 times.

{% hint style="danger" %}
<mark style="color:red;">O Retorno do JSON quando marcado para retornar os dados “Signatários” para este gatilho em específico, retornará somente os dados do signatário que assinou os documentos.</mark>
{% endhint %}

4. **Process rejected by a signatory:** As soon as a signatory refuses to sign a document.
5. **Process canceled by the sender:** As soon as the sender cancels the process submission.
6. **Process expired:** As soon as the process expires, meaning it is not fully signed before the deadline.
7. **Process resent:** As soon as the process is resent to the signatories pending signature. The process can be resent when:

* The signature link expires and you want to update the link for the pending signatories;
* You want to change a pending signatory or simply modify the delivery method for them;
* You want to resend the link to a signatory even if they are not overdue.

8. **Process signed/completed by all signatories:** As soon as the process is fully signed by all the signatories.

### Execution Failures

When data delivery fails, the failure information is recorded in the system for a later attempt to resend, either manually or automatically. The application considers whether the delivery is successful based on the following parameters:

