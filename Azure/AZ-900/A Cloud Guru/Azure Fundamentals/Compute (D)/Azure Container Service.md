---
tags:
topic: "compute"
subTopic: "container_service"
source: "guru"
family: "Azure"
imageNameKey: "Azure_container_service"
cert: "AZ-900"
---
# Azure Container Service

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

Azure Container Service (ACS) delivers cloud-based container orchestration, emphasizing Docker.

> **Question**: Select which Azure service you should choose to run an application with the following requirements: - All software dependencies are bundled with the application source code - Bundled application is portable - Provision and run compute only when needed to save costs - Minimal management overhead
> 
> **Answer**: Containers fulfill the requirement to bundle an application with its dependencies and ensure portability. Azure Container Instances allows you to only run your container when needed and have lower management overhead compared to a fully orchestrated Azure Kubernetes Service option.
## Key Points

- ACS offers streamlined creation, configuration, and management of VM clusters, preconfigured for containerized applications.
- Embraces **containerization** to encapsulate workloads and their dependencies, enhancing portability and dependency management.

### Benefits

- **Dependency Management**: Containers include every required dependency, ensuring uniformity across stages.
- **Overhead Reduction**: Container independence from OS cuts down reliance on OS-level updates.
- **Portability**: Seamless deployment regardless of the environment's OS or hardware.
- **Efficiency**: Simplifies development, deployment, and scaling.
- **Reliability**: Provides consistent behavior across environments.

### Workflow

- Develop an application, containerize it, and deploy to ACS.
- Seamless integration with conventional software development lifecycles.
- **Cost-Efficient**: Only pay for active container instances, optimizing resource usage.