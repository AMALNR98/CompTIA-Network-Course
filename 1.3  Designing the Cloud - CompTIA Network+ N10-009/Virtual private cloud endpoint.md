# Virtual Private Cloud (VPC) Endpoint

**CompTIA Network+ (N10-009)**

## What is a VPC Endpoint?

A **VPC Endpoint** is a **network interface that allows resources within a Virtual Private Cloud (VPC) to securely connect to supported cloud services without using the public internet**.

📌 Think: **VPC Endpoint = Private gateway to cloud services inside your VPC**

---

## OSI Layer

* Primarily **Layer 3 (Network)**
* Security and routing may involve **Layer 4 (Transport)** and **Layer 7 (Application)**

---

## Key Functions

1. **Private Connectivity:** Keeps traffic between VPC and cloud services off the public internet
2. **Security:** Reduces exposure to internet-based threats
3. **Simplified Access Control:** Works with **IAM policies** to control which resources can use the endpoint
4. **Traffic Optimization:** Reduces latency and improves reliability for cloud service access

---

## Types of VPC Endpoints (Cloud-Specific)

| Type                   | Description                                 | Example                                  |
| ---------------------- | ------------------------------------------- | ---------------------------------------- |
| **Interface Endpoint** | Elastic Network Interface (ENI) within VPC  | AWS Interface Endpoint to S3 or DynamoDB |
| **Gateway Endpoint**   | Targets supported services via route tables | AWS Gateway Endpoint to S3 or DynamoDB   |

---

## Benefits

* **Enhanced security** – No exposure to public internet
* **Reliable connectivity** – Reduces latency and bandwidth usage
* **Simplified network architecture** – No need for NAT or Internet Gateway for service access

---

## Common Exam Points

* VPC Endpoint = **private, secure connection from VPC to cloud service**
* Often tested in **scenario questions**: *“How to connect VMs to S3 without internet?”* → Answer: **VPC Endpoint**
* Understand **Interface vs Gateway endpoints**

---

## One-Line Summary

👉 **A VPC Endpoint allows private, secure, and optimized connectivity from a Virtual Private Cloud to cloud services without using the public internet**

---


