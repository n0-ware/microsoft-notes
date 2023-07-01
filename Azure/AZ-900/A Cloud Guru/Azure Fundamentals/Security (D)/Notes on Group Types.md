---
tags:
topic: "groups"
subTopic: "notes"
source: "research"
family: "Azure"
imageNameKey: "Azure_notes"
cert: "AZ-900"
---
# Notes on Group Types
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

## Note from ChatGPT

**Question**: What are the differences between Microsoft groups and Security groups in Azure Active Directory (Azure AD)?

**Answer**: In Azure AD, Microsoft 365 groups and Security groups are two types of groups with distinct purposes. Microsoft 365 groups are focused on collaboration and productivity within Microsoft 365 services, facilitating team-based collaboration and offering features like shared mailbox and calendar. They can have dynamic membership based on predefined conditions. On the other hand, Security groups are primarily used for access control and permissions management across Azure AD and other applications. They have static membership and are commonly used to assign permissions to Azure resources and applications. Microsoft 365 groups cannot be nested inside Security groups directly, but you can combine both groups for access control and collaboration by assigning a Security group as a member of a Microsoft 365 group.

**Question**: Can Microsoft groups be inside a security group or facilitate dynamic assignments?

**Answer**: No, Microsoft 365 groups cannot be directly nested inside a security group in Azure AD. However, you can indirectly use both groups together by assigning permissions to a security group for a resource and adding that security group as a member of a Microsoft 365 group to enable collaboration. Dynamic assignments can be facilitated through Azure AD dynamic group membership, where dynamic groups automatically update their membership based on defined rules and conditions. By utilizing dynamic groups, you can automatically add or remove users from groups based on attributes or rules defined in Azure AD.

**Question**: What methods exist for dynamically assigning permissions to users when onboarded?

**Answer**: Several methods are available for dynamically assigning permissions to users during onboarding in Azure AD. These include:

Azure AD Dynamic Group Membership: Creating dynamic groups that automatically update membership based on defined rules and conditions.
Azure AD Group-based Licensing: Assigning licenses dynamically to users based on their group membership.
Role-based Access Control (RBAC): Defining custom roles with specific permissions and assigning them to users or groups.
Custom Onboarding Processes: Incorporating permission assignment as part of specific onboarding processes using scripting or automation tools.
These methods enable dynamic and automated assignment of permissions based on user attributes, roles, or predefined rules, ensuring users have the appropriate access rights when they join the organization.