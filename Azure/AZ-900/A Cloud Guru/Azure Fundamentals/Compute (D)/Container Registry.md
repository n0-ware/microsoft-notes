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
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

- Source of the containers for [[Azure Container Service]] and [[Kubernetes Service]]
- Keeps track of all current valid container images
- Manages files and artifacts
- When a service needs a new container, request is made to ACR
- Can use strong identity management

## Architecture

- ACR provides images and Kubernetes manages containers in "**clusters**""
- Cluster is a set of machines called "**Nodes**"
- Groups of one or more containers sharing the same infrastructure are called "**pods**" and have a uniform instruction set on how the container is run
- Kubernetes automatically creates new **pods** as load increases above stability
![[1_Azure_container_registry.png]]