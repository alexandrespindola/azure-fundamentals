# Azure Identity, Access, and Security - Challenge Project

## Module: Azure Identity, Access, and Security Summary

This document summarizes the key Azure identity, access, and security concepts covered in the Azure AZ-900 Fundamentals course.

---

## Learning Objectives

Upon completing this challenge, you will be able to:

- Apply concepts learned in a practical environment
- Document technical processes in a clear and structured way
- Use GitHub as a tool for sharing technical documentation

---

## Azure Identity, Access, and Security Overview

### Authentication and Authorization

Understanding the difference between authentication and authorization is fundamental for cloud security.

- **Authentication**: Identifies the person or service seeking access to a resource. It requests legitimate credentials and creates the basis for secure identity principles.
- **Authorization**: Determines the level of access assigned to an authenticated person or service. It defines exactly what data they can access and what actions they can perform.

### Azure Directory Services

Azure provides robust directory services for identity management in the cloud.

- **Microsoft Entra ID**: Features cloud-based identity and access management. Handles user authentication, Single Sign-On (SSO), application management, Business-to-Business (B2B) collaboration, and device management.
- **Microsoft Entra Domain Services**: Offers cloud-based domain services without the overhead of managing domain controllers. It allows running legacy applications (that cannot use modern authentication) in the cloud and automatically synchronizes with Microsoft Entra ID.

### Multi-Factor Authentication (MFA)

MFA provides an additional layer of security for identities by requiring two or more elements for full authentication:

- Something you know (like a password).
- Something you have (like a trusted device or phone).
- Something you are (biometrics like a fingerprint or face scan).

### Conditional Access and External Identities

- **Conditional Access**: Gathers signals to make decisions and enforce organizational policies. Conditions can be based on user/group membership, IP location, the device being used, specific applications, or detected risks.
- **External Identities (B2B and B2C)**: Securely manage access for external partners and customers to your applications and resources.

### Role-Based Access Control (RBAC)

RBAC provides fine-grained access management designed to enforce the principle of least privilege.

- Allows dividing tasks within a team.
- Grants users only the specific access they need to perform their jobs.
- Controls access to both the Azure portal and specific Azure resources.

### Security Models

Azure encourages comprehensive security strategies to protect assets against modern threats.

- **Zero Trust**: A security concept based on the principle of "never trust, always verify" and assuming a breach.
- **Defense in Depth**: A layered approach to protecting computer systems. It provides multiple interdependent levels of protection (Physical, Identity, Perimeter, Network, Compute, Application, and Data), ensuring that an attack on one layer is isolated from the others.

### Microsoft Defender for Cloud

A unified infrastructure security management system that strengthens the security posture of your datacenters.

- Provides continuous monitoring and threat protection across both Azure and on-premises datacenters.
- Offers actionable security recommendations.
- Detects and blocks malware, analyzes to identify potential attacks.
- Enables Just-In-Time (JIT) access control for virtual machine ports to minimize exposure.
