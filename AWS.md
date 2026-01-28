# ☁️ AWS Fundamentals – Complete Notes

This document collects and organizes all AWS concepts explained so far, in a clean **Markdown (MD)** format for study and revision.

---

## 1️⃣ On-Premises vs Cloud Computing

### On-Premises

* You own and manage servers, storage, networking
* High upfront cost
* Manual scaling
* Responsible for security, maintenance, power, cooling

### Cloud Computing

* Infrastructure managed by AWS
* Pay-as-you-go
* Auto scaling
* High availability & global reach

---

## 2️⃣ AWS Shared Responsibility Model

| AWS Responsible For    | Customer Responsible For |
| ---------------------- | ------------------------ |
| Physical data centers  | Data security            |
| Hardware               | OS & patching            |
| Network infrastructure | Application security     |
| Managed services       | IAM configuration        |

---

## 3️⃣ AWS Global Infrastructure

### Regions

* Geographic areas (e.g. eu-west-1)
* Each region is isolated

### Availability Zones (AZs)

* Multiple data centers inside a region
* Designed for fault tolerance

### Edge Locations

* Used by CloudFront
* Cache content closer to users
* Faster delivery

---

## 4️⃣ CDN & Performance

### What is a CDN?

A **Content Delivery Network** delivers content from locations closest to users.

### AWS CloudFront

* AWS CDN service
* Uses Edge Locations

### Benefits

* Low latency
* Reduced server load
* Improved user experience

---

## 5️⃣ AWS Compute Services

### EC2 (Elastic Compute Cloud)

* Virtual servers in the cloud
* Full control over OS

### Containers

* Lightweight application packaging

### ECS / EKS

* Container orchestration services

### AWS Fargate

* Serverless containers
* No server management

---

## 6️⃣ Storage Services

### EBS (Elastic Block Store)

* Block storage for EC2
* Persistent

### EFS (Elastic File System)

* Shared file system
* Multiple EC2 access

### Instance Store

* Temporary storage
* Data lost on stop

### S3 (Simple Storage Service)

* Object storage
* Highly durable

#### S3 Storage Classes

* Standard
* Intelligent-Tiering
* Glacier
* Deep Archive

---

## 7️⃣ Databases on AWS

### Managed Databases

* RDS (MySQL, PostgreSQL)
* DynamoDB (NoSQL)

### In-Memory Databases

* ElastiCache
* MemoryDB for Redis

### Graph Databases

* Amazon Neptune

---

## 8️⃣ Networking

### Amazon VPC

* Virtual private network
* Isolated environment

### Security in VPC

* Security Groups
* NACLs
* Route tables

### DNS

* Domain Name System

### Route 53

* DNS service
* Routing policies
* Health checks

---

## 9️⃣ Decoupling & Messaging

### Tight Coupling

* Components depend directly on each other

### Loose Coupling

* Independent components
* Higher reliability

### SQS

* Message queue
* Standard & FIFO

### SNS (Pub/Sub)

* One-to-many messaging

### EventBridge

* Event-driven architecture

### Polling

* Short Polling
* Long Polling

---

## 🔟 Orchestration & Automation

### Step Functions

* Workflow orchestration
* State machines

### Infrastructure as Code (IaC)

* Manage infrastructure using code

### AWS CloudFormation

* IaC service
* YAML / JSON templates

### Benefits

* Repeatability
* Automation
* Version control

---

## 1️⃣1️⃣ Application Services

### Elastic Beanstalk

* Platform as a Service
* Easy app deployment

### AWS X-Ray

* Application tracing
* Debugging & performance analysis

---

## 1️⃣2️⃣ Migration & Transfer

### AWS Application Migration Service (MGN)

* Lift-and-shift servers
* Minimal downtime

### Database Migration Tools

* AWS DMS

### AWS Snow Family

* Snowcone
* Snowball
* Snowmobile

### AWS Transfer Family

* SFTP
* FTP
* FTPS

### AWS DataSync

* Fast data transfer

### Application Discovery Service

* Discover on-prem apps

---

## 1️⃣3️⃣ Hybrid & Edge

### AWS Outposts

* AWS infrastructure on-prem

### Storage Gateway

* Hybrid storage

### Global Accelerator

* Improve global app performance

---

## 1️⃣4️⃣ DevOps & CI/CD

### CI/CD

* Continuous Integration
* Continuous Delivery

### AWS Development Tools

* CodeCommit
* CodeBuild
* CodeDeploy
* CodePipeline

### CodeArtifact

* Artifact repository

---

## 🎯 Final Memory Tips

* **EC2 = Virtual server**
* **S3 = Object storage**
* **RDS = Managed SQL DB**
* **DynamoDB = NoSQL**
* **SQS = Queue**
* **SNS = Pub/Sub**
* **CloudFormation = IaC**
* **MGN = Lift & Shift**

---

