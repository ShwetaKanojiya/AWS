
<div align="center">
  <img src="AWS Services.jpg" width="800" alt="">
</div>

---

# ☁️ AWS Fundamental Services

This repository explores the core building blocks of AWS — Identity and Access Management (IAM), Elastic Compute Cloud (EC2), and Simple Storage Service (S3) — providing detailed insights into their functionality, use cases, and best practices.

---

## 🔐 AWS IAM (Identity and Access Management)

**AWS IAM** is a powerful service that helps you **securely manage access** to your AWS resources.  
It allows you to create and control users, groups, and roles with fine-grained permissions.

###  Key Components
| Component | Description |
|------------|-------------|
| **Users** | Represent individual people or applications requiring AWS access. |
| **Groups** | Collections of users with similar access needs, simplifying permission management. |
| **Roles** | Grant temporary access to AWS resources for external users or services. |
| **Policies** | JSON-based documents defining permissions (allowed or denied actions) for AWS resources. |

###  Features
- **Fine-grained Access Control** – Define precise permissions for each entity.  
- **Principle of Least Privilege** – Grant only the permissions necessary to perform a task.  
- **Multi-Factor Authentication (MFA)** – Add an extra layer of security for user sign-ins.  
- **Audit & Monitoring** – Track all user activities and permission changes for compliance.  

###  Benefits
- Secure and scalable access management  
- Simplified permission assignment  
- Enhanced accountability through detailed logging  

> **In short:** IAM acts as the **security backbone** of your AWS environment, ensuring only authorized users can access specific resources.

---

## 💻 Amazon EC2 (Elastic Compute Cloud)

**Amazon EC2** provides **resizable compute capacity in the cloud**, allowing you to launch virtual servers — called **instances** — on demand.

###  Key Features
- **Scalability:** Adjust computing power easily to meet your workload demands.  
- **Customizable Instances:** Choose CPU, memory, storage, and networking configurations.  
- **Pre-configured AMIs:** Quickly deploy instances using Amazon Machine Images.  
- **VPC Integration:** Launch instances inside Virtual Private Clouds for secure networking.  

###  Use Cases
- Hosting applications and websites  
- Running machine learning models  
- Performing data analysis and batch processing  
- Developing and testing software in isolated environments  

> **In short:** EC2 is the **computing engine** of AWS — flexible, scalable, and secure.

---

## 🗂️ Amazon S3 (Simple Storage Service)

**Amazon S3** is a **highly scalable object storage service** designed to store and retrieve any amount of data from anywhere on the web.

###  Core Concepts
| Term | Description |
|------|-------------|
| **Bucket** | A container for storing objects (files, videos, images, etc.). |
| **Object** | The actual data (file) stored in S3, identified by a unique key within a bucket. |
| **Storage Classes** | Different tiers (e.g., Standard, Glacier) based on access frequency and cost. |

###  Key Features
- **Unlimited Storage Capacity**  
- **High Durability & Availability (99.999999999%)**  
- **Secure Access Control using IAM Policies**  
- **Versioning, Lifecycle Management, and Replication**  

###  Common Use Cases
- Storing application assets (images, videos, backups)  
- Hosting static websites  
- Data archiving and disaster recovery  
- Storing big data for analytics  

> **In short:** S3 provides **reliable, scalable, and secure object storage** for any data type.

---

##  Summary

| Service | Purpose | Key Benefit |
|----------|----------|--------------|
| **IAM** | Manage access and permissions | Secure and centralized identity control |
| **EC2** | Virtual compute servers | Flexible, scalable cloud computing |
| **S3** | Object storage service | Durable and easily accessible data storage |

---
