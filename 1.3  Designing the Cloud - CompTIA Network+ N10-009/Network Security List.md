# Network Security – Key Components

**CompTIA Network+ (N10-009)**

Network security ensures **confidentiality, integrity, and availability** of network resources.

---

## **1. Firewall**

* **Function:** Controls **inbound and outbound traffic** based on rules
* **Types:**

  * Packet-filtering (Layer 3/4)
  * Stateful (tracks connection state)
  * Next-Generation Firewall (NGFW – Layer 7, application-aware)

---

## **2. Intrusion Detection System (IDS)**

* **Function:** Monitors network traffic for **suspicious activity** and generates alerts
* **Types:**

  * Network-based (NIDS)
  * Host-based (HIDS)
* **OSI Layer:** 3–7

---

## **3. Intrusion Prevention System (IPS)**

* **Function:** Detects and **actively blocks** malicious traffic
* **Difference from IDS:** IDS alerts only, IPS blocks automatically
* **OSI Layer:** 3–7

---

## **4. VPN (Virtual Private Network)**

* **Function:** Secure, encrypted connection over public network
* **Types:** Remote Access VPN, Site-to-Site VPN, SSL VPN, IPSec VPN
* **OSI Layer:** 3–7 (depending on protocol)

---

## **5. Security Groups (SG)**

* **Function:** Virtual firewall for cloud **instances**
* **Stateful:** Yes
* **OSI Layer:** 3–4

---

## **6. Network Access Control Lists (ACLs)**

* **Function:** Controls **subnet-level traffic**
* **Stateful:** No (stateless)
* **OSI Layer:** 3–4

---

## **7. Content Filtering / Proxy Servers**

* **Function:** Blocks unwanted websites, malware, or content
* **Example:** Web proxies, forward proxies, reverse proxies

---

## **8. Load Balancers (for security & performance)**

* **Function:** Distribute traffic, prevent overload, and mitigate DoS impact
* **Layer:** 4–7

---

## **9. Endpoint Security**

* **Function:** Protects devices connected to the network
* **Example:** Antivirus, anti-malware, endpoint detection & response (EDR)

---

## **10. Network Segmentation**

* **Function:** Isolate network segments for security and performance
* **Tools:** VLANs, subnets, firewalls

---

## **11. Cloud Security Features**

* **VPC / VNet Isolation**
* **VPC Endpoints** (private connections to cloud services)
* **IAM Policies** for access control

---

## **Quick Comparison Table**

| Device / Function      | Layer | Stateful? | Key Use                          |
| ---------------------- | ----- | --------- | -------------------------------- |
| Firewall               | 3–7   | Sometimes | Control traffic                  |
| IDS                    | 3–7   | No        | Detect attacks                   |
| IPS                    | 3–7   | Yes       | Detect & block attacks           |
| VPN                    | 3–7   | Yes       | Secure remote connectivity       |
| Security Group         | 3–4   | Yes       | Instance-level firewall          |
| ACL                    | 3–4   | No        | Subnet-level filtering           |
| Proxy / Content Filter | 7     | N/A       | Block malicious content          |
| Load Balancer          | 4–7   | Yes       | Distribute traffic, mitigate DoS |

---

## Exam Tips

* Know **stateful vs stateless devices**
* Associate **OSI layer with each security device**
* Be able to **choose security device for scenario**: e.g., VPN for remote access, ACL for subnet filtering

---

## One-Line Summary

👉 **Network security uses firewalls, IDS/IPS, VPNs, ACLs, security groups, proxies, and segmentation to protect resources and control traffic across networks**

---
