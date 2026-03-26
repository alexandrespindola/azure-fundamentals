# Azure Database Instance - Challenge Project

## Module 3: Cloud Service Types Summary

This document summarizes the cloud service types covered in the Azure AZ-900 Fundamentals course.

---

## Learning Objectives

Upon completing this challenge, you will be able to:

- Apply concepts learned in a practical environment
- Document technical processes in a clear and structured way
- Use GitHub as a tool for sharing technical documentation

---

## Cloud Service Types Overview

### IaaS (Infrastructure as a Service)

The most flexible cloud service type. You configure and manage the hardware for your application.

- Create a pay-as-you-go IT infrastructure by renting servers, virtual machines, storage, networks, and operating systems from a cloud provider
- You have control over the underlying infrastructure
- Examples: Azure Virtual Machines, Azure Virtual Networks

### PaaS (Platform as a Service)

Focused on application development. Platform management is handled by the cloud provider.

- Provides an environment for creating, testing, and deploying software applications without focusing on managing the underlying infrastructure
- The provider handles the platform management (OS, middleware, runtime)
- Examples: Azure App Service, Azure SQL Database

### SaaS (Software as a Service)

Pay-as-you-go pricing model. Users pay for the software they use in a subscription model.

- Users connect and use cloud-based applications over the Internet
- Examples: Microsoft Office 365, email and calendars

---

## Shared Responsibility Model

The responsibility for managing cloud services is shared between the cloud provider and the customer. The level of responsibility varies depending on the service type:

| Responsibility | IaaS     | PaaS     | SaaS     |
| -------------- | -------- | -------- | -------- |
| Data           | Customer | Customer | Customer |
| Devices        | Customer | Customer | Customer |
| OS             | Customer | Provider | Provider |
| Middleware     | Customer | Provider | Provider |
| Runtime        | Customer | Provider | Provider |
| Application    | Customer | Customer | Provider |
| Network        | Provider | Provider | Provider |
| Servers        | Provider | Provider | Provider |
| Storage        | Provider | Provider | Provider |

---

## Use Cases

### When to use IaaS

- Maximum control over infrastructure
- Custom configurations required
- Migrating existing applications to the cloud

### When to use PaaS

- Focus on application development
- Rapid development and deployment
- Built-in scalability and management

### When to use SaaS

- Ready-to-use applications
- Subscription-based pricing
- Minimal IT management required
