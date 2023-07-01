---
tags:
topic: "monitor_and_manage"
subTopic: "monitor_tools"
source: "guru"
family: "Azure"
imageNameKey: "Azure_monitor_tools"
cert: "AZ-900"
---
# Monitoring Tools

> **Creation Date:** `=this.file.cday` **Last Modified:** `=this.file.mday`

Azure provides a suite of monitoring tools that work collectively to provide detailed insights into the performance and health of your Azure resources.

## Log Analytics

Azure Monitor generates a large volume of logs, and Log Analytics serves as the storage and analysis platform for these logs.

- It provides an interface to store, analyze, and monitor logs, such as VM details, disk sizes, VPN connections, etc.
- Enables long-term analysis and complex querying of various metrics.
- Supports pre-built queries and allows for the creation of custom queries.
- Uses the **Kusto Query Language (KQL)** for querying and manipulating data.

## Application Insights

Application Insights is specifically designed for web-based applications, providing performance insights, usage metrics, and identification of bottlenecks.

- Applicable to a variety of services including App Services, Azure VMs, and non-Azure resources.
    - Note: VMs require an installed agent for Application Insights.
- Helps in monitoring application performance, usage patterns, bottleneck detection, and much more.

## Azure Monitor Alerts

Azure Monitor Alerts provide real-time notifications in response to unexpected events in your Azure environment.

- Alerts can be triggered by various conditions, such as unresponsive VMs, excessive CPU usage, or application latency above the defined threshold.
- Alert rules are defined by monitored resources, telemetry, conditions to trigger, and assigned severity levels.
- Actions are managed by Action Groups, which specify the response to the triggered alerts.
    - Action groups define notification targets such as email or SMS.
    - They can also define automation workflows for programmatic responses to specific alert conditions.