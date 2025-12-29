# Cloud Responsibility Matrix

**CompTIA Network+ (N10-009)**

## What is the Cloud Responsibility Matrix?

The **Cloud Responsibility Matrix**, also called the **Shared Responsibility Model**, defines **who is responsible for what** in a cloud environment — the **cloud service provider** vs the **customer**.

📌 Think: **“Security OF the cloud” vs “Security IN the cloud”**

---

## Core Concept

* **Cloud Provider** → Responsible for the **infrastructure**
* **Customer** → Responsible for **data, access, and configurations**

---

## Responsibilities Breakdown

### Cloud Provider Responsibilities

(**Security OF the Cloud**)

* Physical data centers
* Physical servers and storage
* Networking hardware
* Power, cooling, and facilities
* Hypervisor (virtualization layer)

---

### Customer Responsibilities

(**Security IN the Cloud**)

* Data security and encryption
* User access (IAM, passwords, MFA)
* OS configuration and patching (varies by model)
* Application security
* Network controls (firewalls, security groups, NSGs)
* Compliance and data classification

---

## Responsibility by Cloud Service Model

### **IaaS (Infrastructure as a Service)**

| Component              | Provider | Customer |
| ---------------------- | -------- | -------- |
| Physical data center   | ✔        | ❌        |
| Virtualization         | ✔        | ❌        |
| OS & patching          | ❌        | ✔        |
| Applications           | ❌        | ✔        |
| Data                   | ❌        | ✔        |
| Network security rules | ❌        | ✔        |

📌 **Customer has most responsibility**

---

### **PaaS (Platform as a Service)**

| Component        | Provider | Customer |
| ---------------- | -------- | -------- |
| OS & runtime     | ✔        | ❌        |
| Application code | ❌        | ✔        |
| Data             | ❌        | ✔        |
| User access      | ❌        | ✔        |

📌 **Shared responsibility, less customer management**

---

### **SaaS (Software as a Service)**

| Component           | Provider | Customer |
| ------------------- | -------- | -------- |
| Application         | ✔        | ❌        |
| OS & infrastructure | ✔        | ❌        |
| Data                | ❌        | ✔        |
| User access         | ❌        | ✔        |

📌 **Customer responsibility is minimal**

---

## Visual Memory Trick (Exam Tip)

* **IaaS → You manage MOST**
* **PaaS → You manage SOME**
* **SaaS → You manage VERY LITTLE**

---

## Common Exam Scenarios

* **Data breach due to weak passwords** → ❌ Customer fault
* **Cloud outage due to hardware failure** → ❌ Provider fault
* **Misconfigured security group** → ❌ Customer fault
* **Hypervisor vulnerability** → ❌ Provider fault

---

## Why This Matters for Network+

* Explains **cloud security boundaries**
* Helps identify **who is responsible in scenario-based questions**
* Ties into **NSGs, IAM, VPNs, and cloud firewalls**

---

## One-Line Summary

👉 **The Cloud Responsibility Matrix defines how security and management duties are shared between the cloud provider and the customer, varying by IaaS, PaaS, and SaaS models**

---

