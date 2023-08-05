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

Azure Container Service (ACS) is a cloud-based container deployment and management service which provides a platform for Docker container orchestration.

## Key Points

- ACS simplifies the creation, configuration, and management of a cluster of virtual machines that are preconfigured to run containerized applications.
- Containers can package any computing load along with their dependencies, promoting portability and reducing issues associated with dependency management.

### Benefits

1. **Manage Application Dependencies**: All the dependencies are included in the container image which ensures consistency across environments.
2. **Reduced Overhead**: Containers are independent of the operating system reducing the dependency on OS updates.
3. **Increased Portability**: Containers can be deployed virtually anywhere, regardless of the operating system or hardware.
4. **Efficiency**: Development, deployment, and maintenance processes are simplified and scaling becomes easy.
5. **Consistency**: Containers maintain consistency across different environments, providing reliability to operations teams.

### Workflow

- A typical workflow includes creating an application or process (workload), packaging it into a container, and deploying it to Azure Container Service.
- This process integrates smoothly with the standard software development lifecycle (SDLC).
- Utilizing on-demand container instances can provide cost efficiency by only using and paying for resources when they are needed.