---
tags:
topic: "core services"
subTopic: "subscriptions"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Subscriptions
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

> Structure and usage of subscriptions in terms of a neighborhood

- A subscription can have multiple tenants
- In that subscription you have all of the resources such as regions, the various tenants, and the resource groups.
- while accounts are unique, the subscriptions can be numerous. And each manage specific sets of resource groups
- All subscriptions have a single offer type
	- enterprise agreement
	- Certified solution partner
	- Pay as you go
	- Etc.
- Separation of subscriptions enables easy billing management
- Subscriptions can have a trust relationship with Azure Active Directory.
- Each subscription. Can be within. A single management group or structured however the hierarchy makes sense for your deployment. But it must follow the hierarchical standard of Azure.

**Using the example of a neighborhood...**

1. A neighborhood has many elements
2. A yard with a fence has one or many items inside of it
3. A house is inside a yard and may have multiple people, offices, cars, etc. 
	1. Common ownership is generally implied at this level, as it is within the yard
	2. **Tenant** can be seen as people
	3. **Resource Groups** can be seen as the home office, or the garage with cars
