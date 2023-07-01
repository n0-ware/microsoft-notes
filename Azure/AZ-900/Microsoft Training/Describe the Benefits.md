- high availability andscalability
- reliability and predictability
- security and governance
- manageability

## High Availability

- i.e., "Uptime"
- Robust ability for a system to remain during **planned or unplanned** outages.

Thoughts
- For mitigating planned outages
	- Gradual, monitored deployment
	- Easy rollback plan
	- Small deployments "chunks"
	- Frequent deployments
	- IaC/Automations/Pipelines
- For unplanned
	- Ensure Component Redundancy
	- Use built-in multi-az and "availability set" features
	- Health monitoring / probes
	- Automation
	- Have strong security practices
	- Have disaster recovery plans
	- Load testing

**A conscious effort to avoid obscure points of downtime**


## Scalability

*Ability of a system to handle variable demand by adding/removing resources as needed*

- Makes you flexible and a beneficiary of cost at scale
- Separate fluctuating/static traffic
- Not all services/servers are scalable
- Vertical/horizontal scaling
	- Vertical has limits and does not increses availability
	- Horizontal often called "scaling out/in" and has no real limits, though increases complexities
	- Horizontal can also benefit from load balancers