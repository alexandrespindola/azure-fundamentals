# Azure Compute and Networking Services - Challenge Project

## Module: Azure Compute and Networking Services Summary

This document summarizes the key Azure compute and networking services covered in the Azure AZ-900 Fundamentals course.

---

## Learning Objectives

Upon completing this challenge, you will be able to:

- Apply concepts learned in a practical environment
- Document technical processes in a clear and structured way
- Use GitHub as a tool for sharing technical documentation

---

## Azure Compute and Networking Overview

### Azure Compute Services

Azure Compute is an on-demand service that provides compute resources such as disks, processors, memory, networking, and operating systems.

### Azure Virtual Machines (VMs)

Virtual machines are software emulations of physical computers.

- Include virtual processor, memory, storage, and networking.
- An IaaS offering that provides total customization and control.
- Suitable for lift-and-shift migrations to the cloud.

### Virtual Machine Scale Sets and Availability Sets

These features help manage VM availability and adapt to demand automatically.

- **Scale Sets**: Offer load balancing to scale resources automatically. Allows scaling out (adding resources) and scaling in (removing resources) based on needs.
- **Availability Sets**: Ensure VMs are deployed across multiple isolated hardware nodes in a cluster, providing redundancy and availability.

### Azure Virtual Desktop

A desktop and application virtualization service that runs on the cloud.

- Creates a complete desktop virtualization environment without requiring additional gateway servers.
- Supports real multi-session deployments.
- Provides a cloud-based Windows desktop experience accessible from dedicated applications or modern browsers.
- Allows multiple users to log into the same computer simultaneously.

### Azure Container Services

Containers provide a lightweight, virtualized environment designed for scalability and resilience through orchestration. Applications are packaged with their dependencies, sitting on top of the host operating system.

- **Azure Container Instances (ACI)**: A PaaS offering that runs a container or a pod of containers directly in Azure.
- **Azure Container Apps**: A PaaS offering that can load balance and scale containers automatically.
- **Azure Kubernetes Service (AKS)**: An orchestration service for containers, ideal for distributed architectures and large container volumes.

### Azure Functions

A serverless computing service.

- A PaaS offering that supports serverless computing operations.
- Event-driven code runs only when triggered, eliminating the need for server infrastructure during idle periods.

### Azure App Services

A fully managed platform to quickly build, deploy, and scale web apps and APIs.

- Compatible with .NET, .NET Core, Node.js, Java, Python, and PHP.
- A PaaS offering that meets enterprise-grade requirements for performance, security, and compliance.

### Azure Networking Services

Networking connects resources and ensures secure communication.

- **Azure Virtual Network (VNet)**: Allows Azure resources to securely communicate with each other, the internet, and on-premises networks.
  - **Public Endpoints**: Accessible from anywhere on the internet.
  - **Private Endpoints**: Accessible only from within your virtual network.
- **Virtual Subnets**: Segment your network to meet specific organizational and security needs.
- **VNet Peering**: Directly connects your private virtual networks.
- **VPN Gateway**: Sends encrypted traffic between an Azure virtual network and an on-premises location over the public internet.
- **ExpressRoute**: Extends on-premises networks into Azure over a private connection facilitated by a connectivity provider.

### Azure DNS

Provides domain hosting for DNS domains.

- **Reliability and Performance**: Uses a global network of DNS name servers (Anycast networking).
- **Security**: Backed by Azure Resource Manager, enabling role-based access control, monitoring, and logging.
- **Customizable**: Allows using private and fully customized domain names within private virtual networks.
- **Alias Records**: Support pointing directly to an Azure resource.
