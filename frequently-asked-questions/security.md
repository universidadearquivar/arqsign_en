# 🟪 Security

Arquivar has over thirty-one years of experience in providing document, process, and information management services in compliance with Brazilian legislation and the standards of the National Archives Council (CONARQ).

Our solutions serve more than 2,500 customers and 20,000 users.

Based on this expertise, Arquivar developed ArqSign – a platform that allows the electronic and digital signing of documents, fully compliant with Brazilian legislation, ensuring 100% legal validity.

<details>

<summary>Is this type of service already approved by the LGPD?</summary>

ArqSign's goal is to protect the rights of its customers by ensuring complete security for their data. All information collected or processed by ArqSign strictly adheres to the legal provisions of the General Data Protection Law (LGPD).

</details>

<details>

<summary>What happens to a document signed using the ArqSign Platform?</summary>

In the Adobe Reader Subscriptions Panel you can check:

1. To Archive as a certifier of the signature process, at the beginning of the signature trail;
2. A digital certificate identifying each signature action (in the example below we have 2 signatories).
3. Archiving finalizes the signature flow and locks the file to prevent changes.

![](<../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1).png>)

![](<../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)

</details>

<details>

<summary>What type of encryption is used on the ArqSign Platform?</summary>

To ensure the security of data being transferred between the Client and the Server, data is encrypted using a SHA256 SSL certificate.

We use encryption for communications and transaction processes, employing industry-standard transport protocols between user devices and Microsoft Azure data centers, as well as within the data centers themselves.

For data at rest, our Server, Azure, offers a wide range of encryption capabilities up to AES-256.

* **Network Protection** – The infrastructure required to securely connect virtual machines to each other and to connect on-premises data centers to Azure VMs. Azure blocks unauthorized traffic to and from Microsoft data centers using a variety of technologies. Azure Virtual Network extends your on-premises network to the cloud via site-to-site VPN.
* **Threat Management** – Microsoft Antimalware for cloud services and virtual machines. Microsoft also employs intrusion detection, distributed denial of service (DDoS) attack prevention, regular penetration testing, and data analytics and machine learning tools to help mitigate threats against the Azure platform.

</details>

<details>

<summary>Where are the data and documents entered into the ArqSign Platform stored?</summary>

Data and documents are stored in the Microsoft Azure datacenter, a world leader in establishing privacy and security requirements. 

Microsoft Azure meets a wide range of international and industry-specific compliance standards, including GDPR (General Data Protection Regulation), ISO 27001, HIPAA, FedRAMP, SOC 1 and SOC 2, as well as country-specific standards including Australia’s IRAP, UK’s G-Cloud, and Singapore’s MTCS. Rigorous third-party audits, such as those conducted by the British Standards Institute, confirm that Azure adheres to the stringent security controls required by these standards.

Microsoft has leveraged its experience building enterprise software protections and running some of the world’s largest online services to create robust security technologies and practices. These help ensure that Azure infrastructure is resilient to attacks, protect user access to the Azure environment, and help keep customer data safe through encrypted communications and threat management and mitigation practices, including regular penetration testing.

[Click here](https://youtu.be/yKNeahEQY8g) and watch the explanatory video.

</details>

<details>

<summary>What standards base is used as a reference for the ArqSign Platform signature process?</summary>

The ArqSign platform is based on the [DIGITAL SIGNATURE POLICY REQUIREMENTS AT ICP-BRASIL of ITI (National Institute of Information Technology)](https://www.gov.br/iti/pt-br/central-de-conteudo/doc-icp-15-03-requisitos-minimos-para-politicas-de-assinatura-pdf).&#x20;

This document establishes the requirements that must be observed by entities creating Digital Signature Policies within the scope of the Brazilian Public Key Infrastructure (ICP-Brasil), in accordance with the structure proposed by the ETSI TR 102 272 \[1] and ETSI TR 102.038 \[2] standards.

</details>

<details>

<summary>What is the difference between the ArqSign signature and the signature of other platforms on the market?</summary>

ArqSign ensures that the file signed by all participants in the flow is always the same through its exclusive signature process!

Whenever a signatory signs a document without their own Digital Certificate, Arqsign applies a Digital Certificate from the platform, capturing the  _Hash_  (unique identification) of the file, verifies the integrity of the file and attaches the signatory's identification to the Certificate.

When the user already has a digital certificate and wants to use it to sign through ArqSign, we use this certificate to verify the integrity and identify the user as a signatory in the document.

Applying a digital certificate to the document for each signature act is the only possible means of ensuring the security level of the advanced or qualified signature described in Law No. 14,063, of September 23, 2020.

</details>

<details>

<summary>What authentication items are available on the platform?</summary>

ArqSign guarantees a wide variety of authentication technologies, including:

* ICP-Brasil or international standard digital certificates;
* Name(s) of signatory(ies);
* Registration documents of the signatory (CPF, CNPJ or other);
* Email addresses;
* IP address(es) of signatory(ies);
* Capture of the signatory's geolocation (if enabled on the equipment);
* Acceptance term for electronic signature.
* Access code;
* ArqSign Account;
* Visual representation of the signature;
* Date and time of signature;
* Transaction history (i.e. who sent, viewed, signed, etc.);
* Authentication history;
* Completion status.

</details>
