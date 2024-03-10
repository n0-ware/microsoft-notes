---
tags:
topic: "introduction"
subTopic: "monitoring"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Monitoring Azure

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

When managing Azure resources, it's crucial to answer:

1. Are the resources in my tenant functioning as anticipated?
2. Are any errors present in my environment?
3. Who made changes, and what were those changes?

## Azure Monitor

Azure Monitor provides a comprehensive solution, capturing metrics and logs from both Azure and specific non-Azure sources.

### Logs

Logs are textual records detailing events. Examples include:

- **Activity Logs**: Who initiated a resource and when?
- **Operating System Logs**: For instance, why is Windows displaying an error?

### Metrics

Metrics focus on telemetry data to gauge performance, tracking elements like:

- CPU utilization
- Memory usage
- Storage consumption
- Website latency

## Working Mechanism

Azure Monitor functions by:

- Channeling all resource data to appropriate metric and log repositories.
- Aggregating data from diverse sources, including apps, OS, resources, tenants, and custom sources.
- Using the data to enhance monitoring resources like insights and integrations (e.g., Event Hubs).

Key monitoring categories are:

- Insights
- Visualization
- Analysis
- Response
- Integration