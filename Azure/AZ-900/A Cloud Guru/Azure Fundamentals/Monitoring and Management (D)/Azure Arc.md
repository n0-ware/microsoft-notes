---
tags:
topic: "monitor_and_manage"
subTopic: "azure_arc"
source: "guru"
family: "Azure"
imageNameKey: "Azure_azure_arc"
cert: "AZ-900"
---
# Azure Arc

> **Creation Date:** `=this.file.cday` **Last Modified:** `=this.file.mday`

Azure Arc is a service that simplifies the management of complex and distributed computing environments, by providing a unified control plane for resources that span different locations and clouds, including on-premises and other cloud platforms.

## Overview

- Azure Arc helps in managing complex computing environments that span multiple locations, including on-premises and other cloud services.
- A common challenge is that each of these locations or cloud platforms has its own set of management resources, which Azure Arc aims to consolidate.
- Azure Arc brings a solution to the question - _What if we could manage both Azure and non-Azure resources in the same interface and apply governance policies to those non-Azure resources_?

> **Centralized governance and management for on-premises and multi-cloud computing resources**

- Azure Arc enables management of non-Azure resources as if they were in Azure.
- It extends Azure cloud management capabilities and services to non-Azure locations.

![[Azure/AZ-900/A Cloud Guru/Azure Fundamentals/Monitoring and Management (D)/Photos/1_Azure_azure_arc.png]]

## Key Benefits

Azure Arc offers several benefits that enhance the management and governance of diverse computing resources:

1. **Unified Management:** Azure Arc allows for managing Azure and non-Azure resources in the same place, bringing a consistent experience across various platforms.
2. **Kubernetes Management:** Azure Arc enables the management of non-Azure Kubernetes clusters, extending the Azure Kubernetes Service (AKS) capabilities to any infrastructure.
3. **Database Deployment:** Azure Arc allows deploying Azure Managed Database services to non-Azure locations, such as Azure SQL Managed Instances, allowing for consistent data services across environments.
4. **Non-Azure Services Management and Protection:**
    - Monitor non-Azure operating systems alongside your Azure VM's.
    - Enhance security with Microsoft Defender for Cloud, protecting resources across different clouds.
    - Utilize Azure Automation and Runbooks for process automation and configuration management.
5. **Governance:** Apply Azure governance tools such as Role-Based Access Control (RBAC), policies, and blueprints to non-Azure resources for consistent policy enforcement and access control.
6. **Serverless Deployment:** Deploy Azure serverless services to non-Azure hardware, including App Service, Azure Functions, Logic Apps, and more, extending the benefits of Azure's PaaS offerings to other environments.