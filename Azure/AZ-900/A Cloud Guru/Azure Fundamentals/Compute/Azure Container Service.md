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
> *Creation Date:* `=this.file.cday`
> *Last Modified:* `=this.file.mday`

- Any computing load can be packaged with the dependencies, from libraries to operating systems
- Many containers can go on the same system
- Very important part of cloud computing

## Benefits

- Manage application dependencies because all of the dependencies are included in the container image, Allowing management with confidence and consistency
- Less overhead because virtual machines require many more updates, whereas containers don't have any relation to the operating system, so you don't have patch dependency
- Increased portability allows applications running in the containers to be deployed more or less anywhere, with different operating systems and different hardware platforms
- High efficiency in development, deployment and maintenance makes the entire process simpler and scaling easy
- Consistency in Every aspect allows the operations teams to rely on containers being the same every time.

## Workflow

- Normal SDLC
- Throw into a container
- Add to Azure Container Service

1. Workload = process or application
2. ACE is the primary Azure service for container workloads
3. **on demand saves you money**
