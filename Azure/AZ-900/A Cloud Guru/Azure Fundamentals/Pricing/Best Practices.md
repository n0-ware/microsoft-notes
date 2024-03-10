---
tags:
topic: "pricing"
subTopic: "best_practices"
source: "guru"
family: "Azure"
imageNameKey: "Azure_best_practices"
cert: "AZ-900"
---
# Best Practices
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

## Spending Limits
- Some types of accounts have built in spending limits
	- Credit based
- No increase to spending limits possible
	- Either remove or add more credits

## Quotas
- These are set by Azure
- Can request quota increases from Azure support
- e.g., 100 namespaces in Event Hub
- This allows Azure to maintain their service to all customers

## Tags
- Crucial for resources organization
- Best praactices
	- Roles
	- Related Resources
	- Filter by project, reporting
	- Unambiguous

## Long vs Short Term
- Pay as you go is the most expensive
- Reserving instances gives you up to 70% discounts on VMware
- Reserved capacity exists for 1 or 3 year commitment
	- Azure SQL up to 80%
	- Cosmos DB up to 65%
	- Synapse Analytics up to 65%
	- Redis Cache up to 55%
	- Can change regions, scale up or down, and cancel as needed

## BYO License
- You can bring your own license as needed

## Advisor
- Has a cost optimization section
