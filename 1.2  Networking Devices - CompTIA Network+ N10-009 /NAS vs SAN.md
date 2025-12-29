# NAS vs SAN

**CompTIA Network+ (N10-009)**

Both **NAS** (Network Attached Storage) and **SAN** (Storage Area Network) are storage solutions, but they differ in **architecture, access method, and use cases**.

---

## **1. NAS (Network Attached Storage)**

* **Definition:** File-level storage device connected to a network, accessible by clients using **network protocols**.
* **OSI Layer:** Operates mostly at **Layer 7 (Application Layer)** since clients access files over protocols like SMB/CIFS or NFS.

### Key Features

* File-level storage (shares files over network)
* Uses standard network (Ethernet)
* Easy to set up and manage
* Can be accessed by multiple clients simultaneously
* Protocols: **SMB/CIFS**, **NFS**, **FTP**

### Use Cases

* Home or office file sharing
* Backup and archiving
* Media storage

### Pros

* Easy to deploy
* Cost-effective
* Uses existing network infrastructure

### Cons

* Slower than SAN (dependent on network speed)
* Not ideal for high-performance applications

---

## **2. SAN (Storage Area Network)**

* **Definition:** Block-level storage network designed to provide high-speed access to storage devices.
* **OSI Layer:** Operates at **Layer 2/3 (depending on implementation)**; often uses **Fibre Channel (Layer 2)** or **iSCSI (Layer 3)**.

### Key Features

* Block-level storage (appears as a local disk to servers)
* High-speed dedicated network (Fibre Channel or iSCSI)
* Supports multiple servers accessing shared storage
* Often used in enterprise environments

### Use Cases

* Databases
* Virtualization
* High-performance computing
* Large-scale enterprise applications

### Pros

* Very fast and reliable
* Supports clustering and high availability
* Scalable for enterprise needs

### Cons

* Expensive
* Complex setup and management

---

## **Comparison Table: NAS vs SAN**

| Feature         | NAS                   | SAN                          |
| --------------- | --------------------- | ---------------------------- |
| Type of Storage | File-level            | Block-level                  |
| Access Protocol | SMB/CIFS, NFS, FTP    | Fibre Channel, iSCSI         |
| OSI Layer       | 7 (Application)       | 2/3                          |
| Network         | Standard Ethernet     | Dedicated high-speed network |
| Performance     | Moderate              | High                         |
| Use Case        | File sharing, backups | Databases, virtualization    |
| Cost            | Low                   | High                         |
| Complexity      | Easy                  | Complex                      |

---

## Exam Tips

* **NAS = File-level, simple, Ethernet, Layer 7**
* **SAN = Block-level, high-speed, Fibre Channel/iSCSI, Layer 2/3**
* Know examples and use cases
* Performance and cost differences are frequently tested

---

## One-Line Summary

👉 **NAS provides file-level storage over a standard network, while SAN provides high-speed block-level storage over a dedicated network**

---
