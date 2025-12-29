# Networking Functions

**CompTIA Network+ (N10-009)**

Networking functions are the **core services and operations** that allow devices to **communicate, share resources, and access network services**.

📌 Important for the exam: Know **function, purpose, and OSI layer association**

---

## 1. **Routing**

* **Definition:** Directs packets between different networks
* **Device:** Router
* **OSI Layer:** 3 (Network)
* **Function:** Determines **best path** for data delivery using routing tables and protocols like RIP, OSPF, BGP

---

## 2. **Switching**

* **Definition:** Connects devices within the same network and forwards frames based on MAC addresses
* **Device:** Switch
* **OSI Layer:** 2 (Data Link)
* **Function:** Reduces collisions, segments LAN into **collision domains**, supports VLANs

---

## 3. **Segmentation**

* **Definition:** Dividing a network into smaller logical parts
* **Devices:** Switches, VLANs, Routers
* **Function:** Improves performance and security
* **Example:** VLANs separate traffic between departments

---

## 4. **Addressing**

* **Definition:** Assigning unique identifiers to devices
* **Types:**

  * **IP addressing** (IPv4 / IPv6) – Layer 3
  * **MAC addressing** – Layer 2
* **Function:** Ensures data is delivered to the correct device

---

## 5. **Translation**

* **Definition:** Converting addresses or protocols
* **Examples:**

  * **NAT (Network Address Translation)** – private ↔ public IPs
  * **DNS** – domain name ↔ IP address
* **OSI Layer:** 3 (NAT), 7 (DNS)

---

## 6. **Authentication**

* **Definition:** Verifying identity of devices/users
* **Devices/Services:** RADIUS, TACACS+, LDAP
* **OSI Layer:** 7 (Application)
* **Function:** Controls access to network resources

---

## 7. **Traffic Management**

* **Definition:** Controlling data flow for efficiency and QoS
* **Techniques:**

  * **Load balancing** – distributes traffic among servers
  * **QoS (Quality of Service)** – prioritizes traffic (voice/video over regular data)
* **OSI Layer:** 4–7

---

## 8. **Security**

* **Definition:** Protecting network and data from unauthorized access
* **Devices/Techniques:** Firewall, IDS/IPS, VPN, proxies
* **OSI Layer:** 3–7

---

## 9. **Wireless Functions**

* **Definition:** Providing network access over wireless
* **Devices:** AP, WLC
* **Functions:** Coverage, roaming, RF management, security (WPA/WPA2/WPA3)
* **OSI Layer:** 1 (Physical), 2 (Data Link)

---

## Quick OSI Layer Reference for Networking Functions

| Function           | OSI Layer |
| ------------------ | --------- |
| Routing            | 3         |
| Switching          | 2         |
| Segmentation       | 2/3       |
| Addressing         | 2/3       |
| Translation        | 3/7       |
| Authentication     | 7         |
| Traffic Management | 4–7       |
| Security           | 3–7       |
| Wireless Access    | 1–2       |

---

## Exam Tips

* Always associate **function → device → OSI layer**
* Focus on **purpose and real-world example**
* Scenario-based questions often ask **which function is needed for a problem**

---

## One-Line Summary

👉 **Networking functions are services and operations like routing, switching, addressing, and security that enable devices to communicate and access resources efficiently**

---


