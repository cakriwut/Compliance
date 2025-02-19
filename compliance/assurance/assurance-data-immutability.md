---
title: "Data immutability in Microsoft 365"
description: Learn how Microsoft 365 preserves data in discoverable form to address regulatory compliance, internal governance requirements, and litigation risks.
ms.author: robmazz
author: robmazz
manager: laurawi
ms.reviewer: sosstah
audience: ITPro
ms.topic: article
ms.service: O365-seccomp
ms.localizationpriority: medium
search.appverid:
- MET150
ms.collection:
- MS-Compliance
- MS-Compliance-Assurance
f1.keywords:
- NOCSH
ms.custom: seo-marvel-apr2020
titleSuffix: Microsoft Service Assurance
hideEdit: true
---

# Data immutability in Microsoft 365

Regulatory compliance, internal governance requirements, or litigation risks require organizations to preserve email and associated data in a discoverable form. All data in the system must be discoverable and none of it can be destroyed or altered. The industry-standard term for this is "immutability."

Traditional methods for immutability typically worked by moving email messages to a separate, read-only storage location. While such systems serve the purpose of preserving mailbox items for discovery, they often affect the user experience by removing preserved items from the customary daily workflow. For IT professionals, this immutability approach requires the deployment and ongoing maintenance of a separate server and storage infrastructure. Discovery is performed with tools external to the mail system and includes associated deployment and maintenance costs.

Through in-place retention and preservation policy features of archiving in Microsoft 365 and its services, you can preserve and retain many classes of incoming, internal, and outgoing data. This includes:

- Inbound and outbound email communications
- Books and records contained in email form or in shared online documents
- Meeting requests
- Faxes
- Instant messages
- Documents shared during online meetings
- Voicemails

In addition, Microsoft has developed add-on features to allow [archiving of data](https://support.office.com/article/Archiving-third-party-data-in-Office-365-0ce338d5-3666-4a18-86ab-c6910ff408cc) from other sources through integration with third-party data capturing and management solutions. After third-party data is imported, you can apply Microsoft 365 compliance features to the data, including:

- [Litigation Hold](/microsoft-365/compliance/create-a-litigation-hold)
- [In-Place eDiscovery and Hold](/microsoft-365/compliance/manage-legal-investigations)
- [Compliance Search](/microsoft-365/compliance/search-for-content)
- [In-Place Archiving](/microsoft-365/compliance/enable-archive-mailboxes)
- [Mailbox auditing](/microsoft-365/compliance/enable-mailbox-auditing)
- [Retention Policies](/microsoft-365/compliance/retention-policies)

For example, when a mailbox is placed on Litigation Hold, third-party data is preserved. You can search third-party data using In-Place eDiscovery or Compliance Search. Or you can apply archiving and retention policies to third-party data just like you can for Microsoft data. Archiving third-party data in Microsoft 365 helps your organization stay compliant with government and regulatory policies.

Archiving in Microsoft 365 provides Securities and Exchange Commission (SEC) Rule 17a-4-compliant storage. Microsoft 365 preserves permanent files of all data collected in a non-rewriteable, non-erasable format using in-place retention policies and preservation policies, including preservation lock.

Specifically:

- All records stored using the retention policies noted above are retained in a dedicated storage area out of the purview of the ordinary user. Only authorized users can access and search these records, but can't alter or erase them.
- Metadata for each item includes a timestamp used in the calculation of retention duration. Timestamps are applied when a new item is received or created and can't be modified or removed from the metadata.
- Archiving in Microsoft 365 allows users to combine different retention policies and hold actions to create granular retention policies. These policies define the type or location of the items preserved and the duration of preservation.
- The Preservation Lock feature allows users to choose whether to make the policy a restrictive policy. A restrictive policy prohibits anyone from having the ability to remove, disable, or make any changes to the retention policy. This means that once Preservation Lock is enabled, it can't be disabled, and no mechanism will exist under which any data from existing custodians that has been collected by the retention policies in place may be overwritten, modified, erased, or deleted during the preservation period. Further, the hold period set by Preservation Lock may not be shortened or decreased. It may, however, be lengthened, if a legal requirement to continue retention of the stored data, as noted above. Preservation Lock ensures that no one, not even administrators or those with certain control access, may change the settings or overwrite or erase data that has been stored, bringing archiving in Microsoft 365 in line with the guidance set forth in the 2003 Release of SEC Rule 17a-4.

To understand how Microsoft 365 helps you meet regulatory obligations, specifically in relation to Rule 17a-4 requirements, see the [Regulatory requirements for information governance and records management](/microsoft-365/compliance/retention-regulatory-requirements#sec-17a-4f-finra-4511c-and-cftc-131c-d) article and linked [Cohasset Assessment](https://servicetrust.microsoft.com/ViewPage/TrustDocuments?command=Download&downloadType=Document&downloadId=9fa8349d-a0c9-47d9-93ad-472aa0fa44ec&docTab=6d000410-c9e9-11e7-9a91-892aae8839ad_FAQ_and_White_Papers). The Cohasset Assessment also provides an in-depth analysis of Microsoft 365 archiving features and functionalities against each of the requirements under SEC Rule 17a-4 and demonstrates to regulated customers how Microsoft 365 archiving can enable them to meet these requirements.
