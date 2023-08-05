---
tags:
topic: "auth_and_auth"
subTopic: "conditional_access"
source: "guru"
family: "Azure"
imageNameKey: "Azure_conditional_access"
cert: "AZ-900"
---
# Conditional Access Policies

> _Creation Date:_ `=this.file.cday` 
> _Last Modified:_ `=this.file.mday`

Conditional Access is a premium feature incorporated into Azure AD that allows the implementation of if/then policies. These policies regulate access based on certain conditions or signals. If a user meets these signals, access is either granted or denied. This feature works best in tandem with Multi-Factor Authentication (MFA).

## Policy Configurations

- **Assign Signals:** Determine conditions that users and groups must meet for logging in. These can include:
    
    - Which users or groups are trying to log in.
    - Which applications are permitted or denied access.
    - The location from which access is attempted.
    - Whether access is attempted from approved or unapproved devices.
- **Make Access Decisions:** Decide on the action once conditions are met. The possible decisions include:
    
    - Granting access.
    - Blocking access.
    - Requiring MFA.

![[1_Azure_conditional_access.png]]

## Key Considerations

When setting up conditional access policies, several important decisions need to be made:

- Should you enforce MFA for all administrators or users, or some combination thereof?
- Should you block sign-ins for legacy authentication protocols?
- Should you restrict access to specific locations or IP addresses?
- Should you require organization-managed devices for application sign-ins?