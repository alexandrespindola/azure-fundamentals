# Azure Storage Services - Challenge Project

## Module: Azure Storage Services Summary

This document summarizes the key Azure storage services and concepts covered in the Azure AZ-900 Fundamentals course.

---

## Learning Objectives

Upon completing this challenge, you will be able to:

- Apply concepts learned in a practical environment
- Document technical processes in a clear and structured way
- Use GitHub as a tool for sharing technical documentation

---

## Azure Storage Overview

### Azure Storage Accounts

A Storage Account is required to access Azure Storage services.

- Must have a globally unique name.
- Provides access over the internet worldwide.
- Determines the storage services available and the redundancy options applied.

### Azure Storage Services

Azure provides several storage services tailored to different data needs.

- **Azure Blob Storage**: Optimized for storing massive amounts of unstructured data, such as text or binary data.
- **Azure Disk Storage**: Provides virtual disks for virtual machines, applications, and other services to access and utilize.
- **Azure Queue Storage**: A message storage service that provides storage and retrieval for large quantities of messages (up to 64 KB each).
- **Azure Files**: Configures a highly available network file share that uses the standard Server Message Block (SMB) protocol.
- **Azure Table Storage**: Provides a key/attribute store for non-relational structured data with a schemaless design.

### Storage Redundancy and Access Tiers

- **Redundancy Options**: Offers various redundancy strategies to ensure data durability, high availability, and protection against planned or unplanned outages.
- **Access Tiers**: Provides different access tiers to optimize storage costs based on how frequently the data is accessed.

### Migration Options

Tools and services to bring data into Azure.

- **Azure Migrate**: A unified migration platform offering a range of integrated and standalone tools for assessment and migration.
- **Azure Data Box**: A physical appliance provided by Microsoft to transfer large amounts of data to Azure.
  - Can store up to 80 terabytes of data.
  - Useful for moving disaster recovery backups, complying with regulatory needs, or migrating from remote locations with limited or no connectivity.
  - Protects data in a rugged, secure box during transit.

### File Management Options

Tools to manage and interact with files in Azure Storage.

- **AzCopy**: A command-line utility used to copy blobs or files to or from an Azure storage account (one-way synchronization).
- **Azure Storage Explorer**: A graphical user interface (similar to Windows Explorer) that makes it easy to manage storage resources. Compatible with Windows, MacOS, and Linux.
- **Azure File Sync**: Synchronizes Azure and on-premises files bidirectionally. The cloud tiering feature keeps frequently accessed files on-premises while freeing up local storage space.
