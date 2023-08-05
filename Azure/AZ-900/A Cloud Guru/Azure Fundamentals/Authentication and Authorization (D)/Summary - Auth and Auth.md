---
tags:
topic: "auth_and_auth"
subTopic: "summary"
source: "guru"
family: "Azure"
imageNameKey: "Azure_summary"
cert: "AZ-900"
---
# Summary - Authentication and Authorization

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

## Key Concepts

- **Azure Active Directory (AAD):** This cloud-based identity service is fundamental to using Azure. It's not identical to traditional AD, and it's always the first service created in Azure. An AAD tenant represents an organization and is a single instance of Azure AD. A user can be a member of a single tenant and can be a guest in up to 499 other tenants. A subscription within a tenant represents the billing entity.
    
- **Hybrid Cloud and Zero Trust:** Azure AD supports hybrid cloud configurations and embraces the Zero Trust security model. In Zero Trust, every user and device is considered untrusted regardless of location, emphasizing identity over location. This model is crucial for secure remote work.
    
- **Multi-Factor Authentication (MFA):** MFA is a critical security measure that involves at least two of the following: something you know, something you have, and something you are.
    
- **Conditional Access Policies:** These rely on if/then policies, such as requiring MFA or mandating the use of managed devices. They grant or block access based on set conditions.
    
- **Passwordless Authentication:** This method removes the need for system passwords, replacing them with two-factor authentication, using mechanisms like the Microsoft Authenticator app, Windows Hello, or FIDO2 keys.
    
- **Guest Access:** AAD allows collaboration with external users. These guests can come from many different Identity Providers (IDPs) and can be invited instead of creating a new account.
    
- **Azure Active Directory Domain Services (AAD DS):** AAD DS is a managed AD DS service that integrates with Azure AD through a one-way sync. It requires a separate domain and is not an extension of an on-prem domain.
    
- **Single Sign-On (SSO):** SSO enables a single password or passwordless experience, reducing user friction during authentication processes.
    

## Deep Dive - Azure Active Directory Domain Services (AAD DS)

AAD DS is not a direct replacement for traditional AD DS and uses different methods for authentication. This fully-managed service provides classic AD features and comes with built-in high availability, thanks to two domain controllers. However, it doesn't extend your on-prem domain and needs to use a different domain name.

AAD DS supports legacy applications that might struggle with modern authentication methods. If you need to migrate an application to Azure that uses Lightweight Directory Access Protocol (LDAP), Kerberos, or NT Lan Manager (NTLM) for directory services, AAD DS can be an excellent choice.

## Understanding Azure Active Directory

It's crucial to remember that AAD and traditional AD serve different purposes and are not the same. AAD is an online service, designed with web access in mind. When you sign up for Azure, an AAD tenant is created, representing the organization. A tenant is a single instance of AAD, and it is separate from other AAD tenants.

AAD is a part of the broader Microsoft Entra product family and is a prerequisite for other Azure services.

## Managing Access with Conditional Access Policies

Conditional Access Policies in Azure AD provide an if/then approach for user access. If a user meets certain conditions or signals (like their location or whether they're using approved devices), access is either granted or blocked based on preset decisions. These might include whether to grant or block access, or whether to require MFA.

## Facilitating External Collaboration with Guest Access

Azure AD allows collaboration with external users through its Guest Access feature. These guests can be from many different Identity Providers (IDPs). Instead of creating a new account for each guest, Azure AD allows you to send invitations to collaborate.

## Embracing Passwordless Authentication

Passwordless authentication removes the need for system passwords, replacing them with two-factor authentication. Methods include something you have (like a mobile device or key fob), or something you know or are (like a fingerprint, face, or device unlock PIN). This approach enhances security by reducing password-related attacks while offering an improved user experience.

## Leveraging Single Sign-On (SSO)

SSO allows users to log in once and gain access to multiple systems without being prompted to log in again. This feature, available in Azure AD, can significantly enhance the user experience by reducing the need to remember and input multiple sets of credentials.

## Implementing Zero Trust

The Zero Trust security model assumes that no user or device is trusted, regardless of their location. This model puts identity at the center of the trust decisions, allowing secure remote work. Tools such as Conditional Access, Identity Protection, and Access Reviews in Azure AD help implement a Zero Trust model. The mantra of Zero Trust is "Never trust, always verify."