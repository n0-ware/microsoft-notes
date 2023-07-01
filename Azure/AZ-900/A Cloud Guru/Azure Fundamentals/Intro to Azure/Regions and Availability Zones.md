---
tags:
topic: "fundamentals"
subTopic: "regions_and_azs"
source: "guru"
family: "Azure"
imageNameKey: "Azure_fundamentals"
cert: "AZ-900"
---
# Regions and Availability Zones
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`


## Regions 

- Regions > AZs
- Latency-defined perimiter
	- "Not to far from each other"
	- Or "Two more more availability zones connected by fiber"
	- Generally <10ms
- Region has one or more availability zones
- Pricing changes per region
- **Each region is paired with another region in the same geographic area**
	- ...except Brazil south paired with South Central US
- Prevents outage failover.
	- If both fail, one region is prioritized
- Planned updates only effect one region at a time
- Replication can occur across paired regions

## Availability Zones

- Unique physical locations in a region
- Independent data centers
- Three zones minimum per region
- **Storage is automatically replicated across the three AZ in a region because storage is regional**