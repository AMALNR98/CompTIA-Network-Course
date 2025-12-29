# Security Groups & ACLs

**CompTIA Network+ (N10-009)**

These are **network security mechanisms** used in **cloud and on-premises environments** to control traffic flow.

---

## **1. Security Groups (SGs)**

* **Definition:** Virtual firewall applied at the **instance (VM) level** in cloud environments
* **OSI Layer:** Primarily **Layer 3 (Network) and Layer 4 (Transport)**
* **Function:** Controls **inbound and outbound traffic** to/from instances

### Key Features

* **Stateful:** Return traffic is automatically allowed if request is allowed
* **Rules:** Specify allowed traffic by **protocol, port, source/destination IP**
* **Applied to:** Network interfaces of virtual machines (VMs)
* **Default:** Deny all inbound, allow all outbound (varies by cloud provider)

### Example

| Direction | Protocol | Port | Source/Destination |
| --------- | -------- | ---- | ------------------ |
| Inbound   | TCP      | 22   | 10.0.0.0/24 (SSH)  |
| Inbound   | TCP      | 80   | 0.0.0.0/0 (HTTP)   |
| Outbound  | All      | All  | 0.0.0.0/0          |

---

## **2. Network Access Control Lists (ACLs)**

* **Definition:** Stateless firewall applied at the **subnet level**
* **OSI Layer:** Primarily **Layer 3 (Network) and Layer 4 (Transport)**
* **Function:** Controls **inbound and outbound traffic for subnets**

### Key Features

* **Stateless:** Return traffic must have explicit rule
* **Rules:** Can **allow or deny** traffic based on protocol, port, source/destination
* **Applied to:** Subnets or network interfaces

### Example

| Rule # | Direction | Protocol | Port | Source/Destination | Action |
| ------ | --------- | -------- | ---- | ------------------ | ------ |
| 100    | Inbound   | TCP      | 80   | 0.0.0.0/0          | Allow  |
| 110    | Inbound   | TCP      | 22   | 10.0.0.0/24        | Allow  |
| 120    | Inbound   | All      | All  | 0.0.0.0/0          | Deny   |

---

## **Security Groups vs ACLs**

| Feature      | Security Group               | Network ACL                         |
| ------------ | ---------------------------- | ----------------------------------- |
| Scope        | Instance/VM                  | Subnet                              |
| State        | Stateful                     | Stateless                           |
| Default Rule | Deny inbound, allow outbound | Allow all inbound/outbound (varies) |
| Rule Type    | Only allow rules             | Allow and deny rules                |
| OSI Layer    | 3–4                          | 3–4                                 |

---

## Common Exam Points

* Security Groups = **stateful, VM-level**
* ACLs = **stateless, subnet-level**
* Know difference between **allow vs deny rules**
* Frequently tested in **cloud networking and firewall scenarios**

---

## One-Line Summary

👉 **Security Groups control traffic to instances (stateful), while Network ACLs control traffic at the subnet level (stateless) in cloud networks**

---
