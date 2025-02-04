---
tags:
topic: "monitor_and_manage"
subTopic: "az_monitor"
source: "guru"
family: "Azure"
imageNameKey: "Azure_az_monitor"
cert: "AZ-900"
---
# Azure Monitor

> **Creation Date:** `=this.file.cday` **Last Modified:** `=this.file.mday`

Azure Monitor uses all the data Azure collects to improve your cloud management experience.

## Overview

- Azure Monitor is primarily focused on telemetry data, which refers to the collection of measurements or other data at remote or inaccessible points and their automatic transmission to the receiving equipment for monitoring.
- In essence, it is about the performance of services, not the data residing within them.
- Azure Monitor handles all your telemetry data, providing insights about your cloud environment rather than the data it hosts.

## Key Features

1. **Data Feed:** Azure Monitor provides a constant feed from most Azure services in your environment and certain on-premises services.
2. **Centralized Management:** As a fully managed and centralized service, Azure Monitor allows you to manage all your data in one place.
3. **Interactive Query Language:** Azure Monitor supports a highly interactive query language.
4. **Machine Learning Integration:** Azure Monitor uses machine learning to predict and recognize potential issues.
5. **Performance Optimization:** It helps to maximize performance and availability, and assists in issue identification.

## Azure Monitor Alerts

Azure Monitor Alerts provide real-time notifications in response to unexpected events in your Azure environment.

- Alerts can be triggered by various conditions, such as unresponsive VMs, excessive CPU usage, or application latency above the defined threshold.
- Alert rules are defined by monitored resources, telemetry, conditions to trigger, and assigned severity levels.
- Actions are managed by Action Groups, which specify the response to the triggered alerts.
    - Action groups define notification targets such as email or SMS.
    - They can also define automation workflows for programmatic responses to specific alert conditions.