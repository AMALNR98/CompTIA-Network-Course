# Router

**CompTIA Network+ (N10-009)**

## What is a Router?

A **router** is a networking device that **connects two or more different networks** and **forwards packets based on IP addresses**.

📌 Think of it as the **traffic director between networks**.

---

## Key Responsibilities

* **Routing packets** between networks
* **Path selection** (best route to destination)
* **Traffic segmentation** (separates broadcast domains)
* **Network address translation (NAT)**
* Can provide **firewall or VPN functions** in advanced routers

---

## OSI Layer

* Primary: **Layer 3 (Network Layer)**
* Some functions may include Layer 4 (transport) filtering

---

## Router Functions

1. **Packet forwarding** – Uses routing table to send data to correct network
2. **Routing protocols** – Helps routers share network info

   * Examples: RIP, OSPF, EIGRP, BGP
3. **NAT (Network Address Translation)** – Translates private IPs to public IPs
4. **Firewall** – Filters packets based on rules
5. **DHCP (optional)** – Assigns IP addresses to devices

---

## Routing Table

* Stores known networks and the best path to reach them
* Updated by:

  * **Static routing** (manually configured)
  * **Dynamic routing** (routing protocols)

---

## Types of Routers

| Type           | Use Case                                  |
| -------------- | ----------------------------------------- |
| Core Router    | High-speed backbone networks              |
| Edge Router    | Connects internal network to WAN/Internet |
| Virtual Router | Software-based routing                    |

---

## Router Interfaces

* **WAN port** – Connects to external network (ISP)
* **LAN ports** – Connect internal devices/networks
* **Console port** – For configuration
* **Wireless interface** – Optional, for Wi-Fi

---

## Common Router Protocols

* **RIP (Routing Information Protocol)**
* **OSPF (Open Shortest Path First)**
* **BGP (Border Gateway Protocol)**
* **EIGRP (Enhanced Interior Gateway Routing Protocol)**

📌 CompTIA focuses on **concepts, not deep configuration**

---

## Router vs Switch vs Hub (Quick Comparison)

| Feature              | Router            | Switch       | Hub        |
| -------------------- | ----------------- | ------------ | ---------- |
| OSI Layer            | 3                 | 2            | 1          |
| Forwarding           | Packets (IP)      | Frames (MAC) | Bits       |
| Network Scope        | Multiple networks | Single LAN   | Single LAN |
| Traffic Segmentation | Yes               | No           | No         |

---

## Common Router Problems

* Incorrect IP / subnet mask
* Routing table misconfiguration
* Connectivity issue between networks
* NAT or firewall blocking traffic

---

## Exam Tips

* Always associate router with **Layer 3**
* Know the **difference between router and switch**
* Remember **NAT, routing table, IP forwarding**

---

## One-Line Summary

👉 **Router connects multiple networks and forwards packets using IP addresses**


