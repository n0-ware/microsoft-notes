---
tags:
topic: "auth_and_auth"
subTopic: "aadds"
source: "guru"
family: "Azure"
imageNameKey: "Azure_aadds"
cert: "AZ-900"
---
#  Azure Active Directory Domain Services (AAD DS)

> _Creation Date:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

Azure Active Directory Domain Services (AAD DS) is a managed domain services platform on the cloud that presents an entirely different approach to authentication than traditional methods.

## Challenges with Migrating to Azure AD

- Migration to Azure AD can be complicated due to the differences between the new cloud services and traditional domain services.
- AAD DS is not a direct replacement for on-premises AD; it employs entirely different authentication methods.

## Limitations of Azure AD vs AD DS

- **Legacy Applications:** Azure AD might struggle to support legacy applications, specifically those which are incompatible with modern authentication methods like OAuth 2.0.
- **Traditional Authentication Methods:** Some apps might still require traditional AD DS services, such as group policy, LDAP, NTLM, or Kerberos which are not fully supported by AAD DS.

## Potential Solutions

- **Maintain Existing On-Premises AD Servers:** This involves synchronizing your on-premises AD with Azure AD.
- **Set Up an AD Server on Azure VM:** This creates a self-managed AD DS on an Azure VM, which you will be responsible for maintaining.

## Key Features of Azure AD DS

- AAD DS is a **managed** domain services platform on the cloud.
- It offers most of the classic AD features through a managed service.
- It deploys two domain controllers for high availability.

## How AAD DS Works

- Unlike on-premises AD, **you cannot use the same domain name on Azure AD DS.**
- It is not an extension of your on-premises AD, but a standalone service.
- A "one-way sync" can be set up to get all your Azure AD information (including groups, credentials, users, etc.) to Azure AD DS.
- It's also possible to maintain a two-way sync between on-premises AD and Azure AD. This results in a two-way and one-way sync.

![[1_Azure_aadds.png]]

_Please note: Remember to check for the latest updates on Azure AD DS as it is a continually evolving service._