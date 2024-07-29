# ➕ New Document

On the New Document screen, the user will be able to register a document that will be sent to other users (signatories) for signature.&#x20;

## Step 1: Add Documents and Recipients

### Add Documents (Upload files)

To include the documents that need to be signed, drag the desired files to the document upload field or select them for upload from a directory on your device.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

You can include more than one file in the same signing process. In this case, the **"Group files into a single document**" option will be available and can be checked or unchecked.&#x20;

When this option is **checked**, ArqSign displays the **grouped files** in the listing area, where you can change the order of the documents by clicking and dragging them to the desired position. In this case, it is not allowed to change the name of each individual file, only the name of the process.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

To remove a file, click the trash icon available for each file on the screen.&#x20;

When this option is **unchecked**, ArqSign displays the files as **separate items** in the listing area, allowing you to change the order and the names of the files.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">**The following file extensions are allowed:**</mark>

* <mark style="color:orange;">**Document: .doc, .docx, .pdf, .txt**</mark>
* <mark style="color:orange;">**Image: .jpg, .jpeg, .png, .tif, .tiff**</mark>
* <mark style="color:orange;">**Presentation: .ppt, .pptx**</mark>
* <mark style="color:orange;">**Spreadsheet: .csv, .xls, .xlsx**</mark>

<mark style="color:orange;">**Each file can be up to 35MB or up to 2000 pages, and the total file size cannot exceed 100MB.**</mark>
{% endhint %}

In the **"Signature Process Name"** field, you can edit the name of the process that includes the grouped files as needed.

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

In the **"Folder"** field, select the folder where the document will be stored. The folders where documents can be saved must be created in the [Directories > Documents](../directories/documents/) menu. By default, a folder with the user's name is created and should be selected if no other folder exists.

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

Finally, to schedule the automatic renewal of the documents being registered, check the box for the **"Schedule renewal \_\_\_ months after completion of signatures"** field, specifying the number of months you want to be notified about the renewal process. Once the signatures for the initial submission are completed, the system will start counting the specified period. When the renewal period is reached, the person responsible for the documents (sender) will receive a notification indicating that the documents are ready to be renewed.

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

## Advanced settings

Advanced settings pertain to document configurations. You can adjust these settings either as a default for all documents, meaning a standard configuration for every time signatures are needed, or configure options for a specific document individually. To access the full list of options that can be configured for documents, go to the [Administration > Account > Settings](../administration/administration/account.md#settings-tab) menu. Below are all the general configurable options:

**Document expiration time after sending:** In this field, the user should specify the expiration period (in days) for the document, which is the deadline for recipients to sign it.

{% hint style="warning" %}
<mark style="color:orange;">If this field is not modified, it will be filled with the default value. The system default is 120 days, but this value can be changed in the</mark> [<mark style="color:orange;">**Administration > Account > Settings menu.**</mark>](../administration/administration/account.md#settings-tab)
{% endhint %}

**Warning before expiration:** In this field, specify the period (in days) before which the system should send a warning to recipients who have not yet signed about the document's expiration.

**Enable reminders:** By enabling this option, the system will send reminders to recipients to sign the document. These reminders will only be sent to signatories who have not yet signed the document. By default, this option will be checked.

**Send reminders to recipients every:** In this field, specify how often (in days) the system should send signing reminders to recipients who have not yet signed.

**Require signatories to read documents before signing:** This setting requires that signatories read the documents before signing. This information will be checked or unchecked based on the account configuration.

**Generate document access QR Code in Signature Record:** By enabling this option, a QR Code will be generated in the document's signature record. By default, this option will be unchecked.

When you hover over the "Advanced Settings" option, a tooltip will appear showing a preview of the configured settings.

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

To edit the settings for a specific file, click on **Advanced Settings**, as shown in the image below.

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

***

## Recipients&#x20;

In the "Recipients" field, fill in the details for the signatories who will receive the document and participate in the signing process. The following settings need to be configured for each recipient:

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

You can add a recipient from a saved contact list by clicking the **"Add recipient from my contact list"** icon.

{% hint style="info" %}
<mark style="color:blue;">**Important**</mark><mark style="color:blue;">: The contact list must be created beforehand in the</mark> [<mark style="color:blue;">"My Profile"</mark>](my-profile.md) <mark style="color:blue;">menu.</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

When you click this button, the list will be displayed. To add the desired recipients, select them by clicking the checkbox next to their names and then click "Add Recipients."

<figure><img src="../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

By checking the **"Sign in the order below"** checkbox, the document will be sent to recipients in the order specified in the "**Order**" field, which will appear at the top of the "Recipient Details" section. With this option set, a recipient will only receive the document once the previous recipient has completed their signing action.

{% hint style="warning" %}
<mark style="color:orange;">**If the previous user only had viewing actions, the next signatory will receive the document once the last signatory before them has completed their signing.**</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

**Recipient Name:** Enter the name of the recipient.

**Send via:** Choose whether the document will be sent via email or WhatsApp to the recipient.

{% hint style="warning" %}
<mark style="color:orange;">**The WhatsApp sending option will only be displayed if the user's account has WhatsApp message credits.**</mark>
{% endhint %}

Depending on the option chosen earlier, provide the recipient's email address or phone number for sending the document.

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

**This recipient will:** Specify whether the recipient will sign the document online as an individual, a legal entity, or both, or if they will only receive a copy of the document at the end of the signing process.

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

If it has been determined that the recipient will sign as an individual or a legal entity, you need to define their role in the signing process. Select from one or more of the listed roles or add a custom "Signer Role" by clicking on "Add Role."

<div>

<figure><img src="../.gitbook/assets/10 (1) (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

 

<figure><img src="../.gitbook/assets/11 (1) (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

</div>

The signer roles presented here are previously created in the menu [Administration > Account > Settings Tab > Signer Role](../administration/administration/account.md#documents-sub-tab). By default, the platform shows the roles "Contracted," "Contractor," "Guarantor," and "Tenant," but you can edit or delete these roles, as well as create new ones if necessary.

**Signature Type:** Select whether the recipient should use an electronic signature or a digital certificate to sign the document.

<figure><img src="../.gitbook/assets/12 (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>



{% hint style="info" %}
<mark style="color:blue;">**ELECTRONIC SIGNATURE VS. DIGITAL SIGNATURE (ICP Brazil and Other ICPs)**</mark>

<mark style="color:blue;">An</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**electronic signature**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">does not require a digital certificate. It is more commonly used for signing contracts and documents between private parties (B2B, B2C).</mark>

<mark style="color:blue;">A</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**digital signature**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">requires a digital certificate. It is more commonly used for issuing invoices and for transactions with the government.</mark>

<mark style="color:blue;">On the Arqsign Platform, when configuring a signature flow, you can determine which type of signature should be executed by the recipient by choosing between:</mark>

<mark style="color:blue;">**a) Electronic Signature**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">(ArqSign produces advanced electronic signatures with legal validity according to MP 2.200-2 of 24/08/2001 and Law 14.063 of 23/11/2020). Whenever a signer electronically signs a document, Arqsign applies its own platform digital certificate, capturing the unique file Hash, verifying the file's integrity, and attaching the signer's identification to the certificate.</mark>

<mark style="color:blue;">**b) Digital Signature – ICP-Brasil or Others**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">(ArqSign produces qualified digital signatures in accordance with MP 2.200-2 of 24/08/2001 and Law 14.063 of 23/11/2020). When the user already has a digital certificate and wishes to use it to sign via ArqSign, this certificate is used to verify the integrity of the signature and to identify the user as the signer on the document.</mark>
{% endhint %}

By selecting the option "Save this recipient in my contact list," the recipient's information will be automatically saved to the user's contact list.

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

**"Security Code" Icon:** Clicking this icon will generate a numeric code that will be sent to the recipient so they can access the document. The code can be generated automatically by the system or manually entered by the user.

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

After generating the code, choose whether it will be sent by email, WhatsApp, or SMS, and provide the email or phone number for sending. It is also possible not to send the code, leaving it up to the user to inform the recipient in the way they prefer. To delete the created code, simply click on "Delete Security Code."

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

If the option to send via WhatsApp is selected, it is possible to allow the recipient to request the code to be resent by checking the **"Allow this recipient to request security code resend"** checkbox.

{% hint style="warning" %}
<mark style="color:orange;">**Each resending of the security code requested by the recipient will consume one WhatsApp credit from the account of the user sending the document.**</mark>
{% endhint %}

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

**Private Message Icon:** By clicking this icon, you can insert a message that will be sent to the recipient along with the document. To do this, fill in the "Subject" and "Message" fields. If you wish to delete the message, click on **"Delete Private Message."**

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

The **Security Code** and **Private Message** items are expandable, and when collapsed, they feature an edit icon, indicating to the user that they can be modified.

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

To add other recipients, click the "Add New Recipient" button. If you wish to include yourself as a recipient, click "Add me as a recipient." The name and email fields will be automatically filled with the information registered in your user profile, and the "Send via" field will be filled with the "Email" option.

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

&#x20;

***

## Default Message

In the "**Default Message"** field, the default message to be sent to all recipients must be defined by filling in the "Subject" and "Message" fields.&#x20;

{% hint style="warning" %}
<mark style="color:orange;">**In the case of recipients who have the Custom Message fields filled, the provided message will be sent in place of the default message.**</mark>&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/18 (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

After completing these settings, click "**Next**" to proceed to the next step, "Save as Draft" to save the document as a draft, or "Delete" to cancel the registration.

<figure><img src="../.gitbook/assets/19 (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

## Step 2: Configure Fields

In the next step, the documents inserted in the previous stage will be displayed in PDF format, and the areas where participants in the process should sign need to be configured.

<figure><img src="../.gitbook/assets/20 (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

### Signature Fields&#x20;

In the right corner of the screen, choose between "**Position signatures manually**" to select where the signature areas will be placed in the document, or "**Automatically place signatures on the page of the document**" so that all signatures are inserted at the end of the last page of the document.&#x20;

For each recipient added in the first step, it is necessary to configure the signature area. To do this, select the recipient in the "**Settings for**" field.&#x20;

<figure><img src="../.gitbook/assets/21 (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

If the option **"Position Signatures Manually"** was chosen, the **"Signature Fields"** section will be displayed. To create the signature area, drag the **"Sign as Individual"** box to the part of the document where you  want the signature to be inserted.

<figure><img src="../.gitbook/assets/img04.png" alt=""><figcaption></figcaption></figure>

The signature area as an individual with the signatory's name will be inserted into the document. It will be possible to resize, enlarge, shrink, and position the signature area by dragging with the cursor or using the arrows.

<figure><img src="../.gitbook/assets/img05.png" alt=""><figcaption></figcaption></figure>

If the recipient will also sign as a legal entity, click on **"Sign as Corporate"** and repeat the process. To delete a signature area, click on the **"Delete"** icon above the area.

<figure><img src="../.gitbook/assets/img06.png" alt=""><figcaption></figcaption></figure>

If the option "**Automatically place signatures on the page of the document**" has been chosen, a page will be inserted at the end of the document where signatures and signatory information will be displayed in an orderly manner. The role that the signer has in the contract is also displayed.

If in [step 1](new-document.md#step-1-add-documents-and-recipients) it was defined that the recipient will sign as an individual and a legal entity, two boxes with their names in the same color should be inserted. The boxes for each of the recipients will be displayed in different colors to visually signal where each should sign.&#x20;

{% hint style="warning" %}
<mark style="color:orange;">**Note that the boxes for recipients are of the same color as shown in the "Settings for" field.**</mark>&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/23 (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

***

### Complementary Signature Information&#x20;

Depending on the type of signature defined for the recipient in step 1, the "**Complementary signature Information**" fields will be displayed. These fields will only be shown if the option "Electronic Signature" was chosen in step 1 in the "Signature Type" field.&#x20;

If the signature is as an Individual, it is possible to require the recipient's name and some document by selecting the options "Individual's Name" and "Individual's Document" as mandatory fields.&#x20;

<figure><img src="../.gitbook/assets/24 (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

<mark style="color:purple;">To require a document, select the desired option among CPF, CNH, RG, or others. If the last option is selected, you will need to provide the document's name, specify if it is text or numeric, and indicate the number of characters.</mark>&#x20;

If the signature is as a Legal Entity, it is possible to require the recipient's company name and some document by selecting the options "Legal Entity Name" and "Legal Entity Document" as mandatory fields.&#x20;

To require a document, select the desired option among Driver's License, Identity or others. If the last option is selected, you will need to provide the document name, specify if it is text or numeric, and indicate the number of characters.

<figure><img src="../.gitbook/assets/25 (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

If the signature is as a Legal Entity, it is possible to require the recipient to provide the company's legal name and some document by checking the options "Legal Entity Name" and "Legal Entity Document" as mandatory fields.

***

### Attachments&#x20;

In the "Attachments" section on the left side of the screen, configurations will be displayed that allow recipients to attach other files to the document at the time of signing. To enable this, check the option "**Allow attaching documents**."&#x20;

Provide the name of the attachment that will be requested and specify whether it will be mandatory to fill in and if all participating recipients in the signature workflow will be able to view the file attached by the recipient.&#x20;

It is possible to request more than one attachment by clicking on the "**Add**" icon.&#x20;

<figure><img src="../.gitbook/assets/26 (1).png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>

By clicking "**Delete,**" the document will be deleted. Clicking "**Save as Draft**" will save the document in the Drafts folder. To edit the document or recipients, click "**Previous Step**." Once the signature field configurations are completed, click "**Send**" to submit the document for the recipients' signatures.&#x20;

<figure><img src="../.gitbook/assets/27.png" alt=""><figcaption><p>Click on the image to enlarge.</p></figcaption></figure>
