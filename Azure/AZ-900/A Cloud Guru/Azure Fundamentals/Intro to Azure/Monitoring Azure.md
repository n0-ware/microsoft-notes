---
tags:
topic: "introduction"
subTopic: "monitoring"
source: "guru"
family: "Azure"
cert: "AZ-900"
---
# Monitoring Azure
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

1. Are the resources in my tenant performing as expected
2. Are there errors in my environment that I should be aware of
3. Who was making changes to the environment and what changes were made?

## Azure Monitor

> Answers all of these questions and logs all metrics from Azure and some non Azure sources.

tl;dr, "Whats happening?"

### Logs

> text based records of events.

- activity logs, as in who created the resource and when?
- Operating system logs such as. Why is window giving me an error?

### Metrics

- Exclusively telemetry based data to track performance
- Items such as CPU utilization or memory or storage or website latency.

## How it works

- All resources are piped through to the various stores of metrics and logs
- The sources as mentioned above can include applications, operating systems, resources, the entire tenant, and custom sources
- These log stores or metric stores populate the various monitor resources such as insights, visualizations and integrations like Event Hubs.
- The categories of monitor sections are
	- insights
	- Visualize
	- Analyze
	- Respond
	- Integrate
