# Network Security Group (NSG)

**CompTIA Network+ (N10-009)**

## What is a Network Security Group?

A **Network Security Group (NSG)** is a **virtual firewall used to control inbound and outbound traffic at the subnet or VM level** in cloud environments.

📌 Think: **NSG = Cloud-based firewall for virtual networks and resources**

---

## OSI Layer

* Primarily **Layer 3 (Network) and Layer 4 (Transport)**

---

## Key Functions

1. **Traffic Filtering:** Allows or denies traffic based on rules
2. **Applied at Multiple Levels:** Subnet-level or individual VM-level
3. **Inbound and Outbound Rules:** Define which traffic is allowed or blocked
4. **Stateful:** Return traffic for allowed flows is automatically permitted
5. **Integration:** Works with cloud services, VNets, and virtual appliances

---

## Common Rules in NSGs

| Direction | Protocol | Port | Source / Destination | Action        |
| --------- | -------- | ---- | -------------------- | ------------- |
| Inbound   | TCP      | 80   | 0.0.0.0/0            | Allow (HTTP)  |
| Inbound   | TCP      | 443  | 0.0.0.0/0            | Allow (HTTPS) |
| Outbound  | All      | All  | 0.0.0.0/0            | Allow         |

---

## NSG vs Security Group

| Feature   | NSG          | Security Group (SG)       |
| --------- | ------------ | ------------------------- |
| Scope     | Subnet / VM  | VM / Instance             |
| State     | Stateful     | Stateful                  |
| Layer     | 3–4          | 3–4                       |
| Cloud Use | Azure        | AWS (or generic cloud SG) |
| Rules     | Allow / Deny | Only Allow                |

---

## Benefits

* **Secure cloud network traffic**
* **Granular control** over subnets and VMs
* **Centralized management** of network access
* **Stateful filtering** reduces configuration complexity

---

## Common Exam Points

* NSG = **stateful firewall for cloud VNets or subnets**
* Know **inbound/outbound rules, Layer 3/4, and scope differences vs Security Groups**
* Scenario questions may ask: *“How to restrict traffic to a subnet in the cloud?”* → Answer: **NSG**

---

## One-Line Summary

👉 **A Network Security Group is a cloud-based, stateful firewall that controls inbound and outbound traffic for subnets or virtual machines**

---

