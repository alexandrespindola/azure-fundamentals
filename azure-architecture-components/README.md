# Azure Architecture Components - Challenge Project

## Module: Azure Architecture and Services Summary

This document summarizes the key Azure architecture components covered in the Azure AZ-900 Fundamentals course.

---

## Learning Objectives

Upon completing this challenge, you will be able to:

- Apply concepts learned in a practical environment
- Document technical processes in a clear and structured way
- Use GitHub as a tool for sharing technical documentation

---

## Azure Architecture Components Overview

### Regions

Regions provide flexibility and scale to reduce customer latency and preserve data residency with comprehensive compliance offerings.

- Azure offers more global regions than any other cloud provider, with over 60 regions representing more than 140 countries.
- Regions are composed of one or more geographically close datacenters.

### Availability Zones

Availability zones provide protection against downtime due to datacenter failures.

- Physically separate datacenters within the same region.
- Each datacenter is equipped with independent power, cooling, and networking.
- Connected via private fiber-optic networks.

### Region Pairs

Region pairs offer enhanced resilience and reliability.

- Minimum of 300 miles of separation between region pairs.
- Automatic replication for certain services.
- Prioritized region recovery in the event of an outage.
- Updates are rolled out sequentially to minimize downtime.

### Azure Sovereign Regions

Sovereign regions meet dedicated security and compliance needs.

- **US Government Services**: Meets the needs of US federal, state, and local agencies and their solution providers.
- **Azure Government**: A separate instance of Azure, physically isolated from non-US government deployments and accessible only to verified and authorized personnel.

### Azure Resources and Resource Groups

Resources are the fundamental components to build cloud solutions.

- **Azure Resources**: Components such as storage, virtual machines, and networks available for building cloud solutions.
- **Resource Groups**: A container used to manage and aggregate resources in a single unit.
  - Resources can exist in only one resource group but can span different regions.
  - Resources can be moved between resource groups.
  - Applications can utilize multiple resource groups.

### Azure Subscriptions

A subscription provides authenticated and authorized access to Azure accounts.

- **Billing Boundary**: Generates separate billing reports and invoices for each subscription.
- **Access Control Boundary**: Manages and controls access to the resources that users can provision with specific subscriptions.

### Management Groups

Management groups provide a level of scope above subscriptions.

- They can include multiple Azure subscriptions.
- Subscriptions inherit conditions and policies applied to the management group.
