---
tags:
topic: "compute"
subTopic: "functions"
source: "guru"
family: "Azure"
imageNameKey: "Azure_functions"
cert: "AZ-900"
---
# Functions

> _Creation Date:_ `=this.file.cday` _Last Modified:_ `=this.file.mday`

Azure Functions is a serverless compute service that allows you to run small pieces of code (referred to as "functions") without worrying about application infrastructure. It is a part of Azure's compute options, alongside Infrastructure as a Service (IaaS) and Platform as a Service (PaaS).

## Key Points

- Azure Functions represents the evolution of cloud computing, abstracting away even more infrastructure considerations than IaaS or PaaS.
- Unlike IaaS or PaaS, Azure Functions does not give you access to the underlying operating system. Your functions are run in a managed environment.
- Functions can be very small, even as small as a single function or operation, or they can be grouped together to perform more complex tasks.
- Functions are invoked via a URL or by events such as changes to data in an Azure Storage account, or a message arriving in an Azure Queue.
- They are ephemeral, meaning they run when triggered and then stop, minimizing the cost as you only pay for the compute time your functions actually consume.
- Azure Functions supports a variety of programming languages, including C#, Java, JavaScript, TypeScript, and Python.

Azure Functions enable developers to focus solely on business logic and ignore infrastructure concerns, making it ideal for building microservices, integrating systems, enabling real-time stream processing, and automating workflows.