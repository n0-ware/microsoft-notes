---
tags:
topic: "compute"
subTopic: "container_registry"
source: "guru"
family: "Azure"
imageNameKey: "Azure_container_registry"
cert: "AZ-900"
---
# Container Registry

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

Azure Container Registry (ACR) is the repository for container images utilized by [[Azure Container Service]] and [[Azure/AZ-900/A Cloud Guru/Azure Fundamentals/Compute (D)/Scale Sets - Kubernetes Service |Scale Sets - Kubernetes Service]].

## Key Points

- Serves as the centralized storage for all active container images.
- Administers files and other essential artifacts.
- Container service requests are directed to ACR when new containers are needed.
- Incorporates robust identity management capabilities.

## Architecture

- ACR supplies the images, while Kubernetes orchestrates the containers within "**clusters**".
- A "**cluster**" comprises a group of machines referred to as "**Nodes**".
- "**Pods**" refer to collections of one or more containers that share the same infrastructure and execute based on a standardized set of instructions.
- Kubernetes dynamically spawns new **pods** in response to an influx in load, ensuring stability.

![[Azure/AZ-900/A Cloud Guru/Azure Fundamentals/Compute (D)/Photos - Compute/1_Azure_container_registry.png]]