---
tags:
topic: "auth_and_auth"
subTopic: "summary"
source: "guru"
family: "Azure"
imageNameKey: "Azure_summary"
cert: "AZ-900"
---
# Summary - Auth and Auth
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

## Global

- AAD is fundamental
	- Cannot use anything without it
	- Not the same as AD
- AAD is first and always created
- Tenant = Organization
	- A single instance of Azure AD
	- A user can be a member of a single tenant and can be a guest of up to 499 tenants
- Subscriptions are the billing identity
	- All services belong to a subscription
- Hybrid cloud is AAD friendly
- Zero trust means everyone is untrusted
	- Regardless of locations
	- Identity vs location needed for remote work
- MFA is crucial
	- Something you...are,have,know
- Conditional access rely on if/then policies
	- such as requiring MFA or be on managed devices
- Passwordless auth removes the system password and replacing with MFA
	- Auth app
	- Hello
	- FIDO2 keys
- Guest access allows external collaboratores
	- Invite vs create a new account
	- Works with many IDPs
- AA DDS is a managed AD DS service
	- Fully managed
	- Integrations
	- One way with from AAD
	- Requires a separate domain
	- Not an extension
- SSO allows for a single password or passwordless experience
## AAD Domain Services

Azure Active Directory (AAD) Domain Services is not a replacement for the traditional Active Directory Domain Services (AD DS). It uses different methods for authentication and it's important to recognize the limitations when dealing with legacy applications, as they might struggle with modern authentication methods. Azure AD DS is a managed service that provides classic AD features, with two domain controllers for high availability. It doesn't extend your on-premises domain but is a standalone service that can synchronize with your Azure AD.

Azure Active Directory Domain Services supports LDAP, Kerberos, and NTLM authentication, which are protocols widely used in enterprise environments. It can be useful when you want to lift-and-shift an application to Azure that uses LDAP to connect to your directory.

## Azure Active Directory

Azure Active Directory (AAD) and traditional Active Directory (AD) serve different purposes and have significant differences. AAD is primarily a cloud-based service, which means it's designed for the web. An organization gets a dedicated instance of AAD upon signing up, called a tenant. The tenant is separate and distinct from other AAD tenants. A subscription within the tenant represents the billing entity. Azure AD is also part of the broader Microsoft Entra product family.

AAD provides capabilities such as Identity Governance, Privileged Identity Management, and Access Reviews to ensure secure access to your resources. Additionally, Azure AD also provides device registration services, enabling device-based conditional access policies and seamless single sign-on experiences. It is important to understand that Azure AD is not a cloud version of Windows Server Active Directory.

## Conditional Access Policies

Conditional Access Policies in Azure AD are a premium feature used to create if/then policies for user access, based on conditions (signals) and decisions. Signals can include the user trying to log in, the application they are trying to access, their location, and whether they are using approved devices. Decisions can include whether to grant or block access, or whether to require multi-factor authentication (MFA).

These are an integral part of Azure AD's defense-in-depth security model. They provide granular control and allow enforcing organizational policies. For example, they can enforce MFA for all administrative roles or block sign-ins from certain locations.

## External Guest Access

Azure AD allows external guests, such as contractors or testers, to access your system via B2B collaboration. Guests can be invited from a variety of identity providers (IDPs) and assigned permissions and applications within your Azure AD.

Azure AD B2B collaboration enables sharing of resources across companies. Each user can be a member of one tenant and a guest in multiple others. Users invited as guests retain the settings from their home organization, providing an additional level of security.

## Identity Services

Identity Services is concerned with authentication (confirming an entity's identity) and authorization (determining what an authenticated entity is allowed to do).

## Multi-Factor Authentication

Multi-Factor Authentication (MFA) involves using at least two ways to prove your identity. This could involve something you know (like a username and password), something you have, something you are (biometrics), or somewhere you are.

In the context of MFA, it's important to note the difference between "push" notifications (the default, most secure method) and "one-time" codes. Also, be aware of "App Passwords", a feature for older applications that don't support modern authentication.

## Passwordless Authentication

Passwordless authentication seeks to remove the need for passwords in system logins, instead relying on two secure single-factor methods of authentication. These methods might include something you have (like a mobile device or key fob), or something you know or are (like a fingerprint, face, or device unlock PIN).

Passwordless authentication methods provide a balance between security and user experience. These methods also reduce the risks associated with password-related attacks, such as password spraying or credential stuffing.

## Azure Active Directory Seamless Single Sign On

Azure Active Directory Seamless Single Sign On (SSO) must first be enabled before it can be used for applications that support it.

This feature provides users with easy access to cloud-based applications without needing any additional on-premises components. It automatically signs users in when they are on their corporate devices connected to your corporate network.

## Zero Trust Concepts

The Zero Trust security model assumes no one is trusted, regardless of location. Trust is based on identity, not location. The model operates on a principle of least privilege, granting just enough access for an entity to perform their tasks. Zero Trust can be used alongside the classic trust model for enhanced security.

The Zero Trust model extends not just to users, but also to devices, networks, and applications. Azure AD provides tools to implement a Zero Trust model with features like Conditional Access, Identity Protection, and Access Reviews. Remember the mantra of Zero Trust: "Never trust, always verify."