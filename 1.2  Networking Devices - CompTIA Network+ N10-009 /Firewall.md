# Firewall

**CompTIA Network+ (N10-009)**

## What is a Firewall?

A **firewall** is a network security device that **monitors and controls incoming and outgoing network traffic** based on **predefined security rules**.

📌 Think of it as a **gatekeeper protecting your network**.

---

## OSI Layer

* Can operate at multiple layers:

  * **Layer 3 (Network)** → Packet filtering
  * **Layer 4 (Transport)** → TCP/UDP port filtering
  * **Layer 7 (Application)** → Deep inspection of application data

---

## Key Responsibilities

* **Traffic filtering** (allow/block based on IP, port, protocol)
* **Protects internal network** from external threats
* **Monitors network activity**
* **Supports VPN connections**
* **Prevents unauthorized access**

---

## Types of Firewalls

| Type                            | Description                                                     | OSI Layer |
| ------------------------------- | --------------------------------------------------------------- | --------- |
| Packet Filtering Firewall       | Filters traffic based on IP addresses, ports, protocols         | L3/L4     |
| Stateful Inspection Firewall    | Monitors connection state and context                           | L3/L4     |
| Proxy Firewall                  | Acts as intermediary between client & server                    | L7        |
| Next-Generation Firewall (NGFW) | Includes IDS/IPS, deep packet inspection, application awareness | L7        |

---

## Firewall Functions

1. **Packet Filtering**

   * Examines headers of packets
   * Allows or blocks based on rules

2. **Stateful Inspection**

   * Tracks state of connections
   * Allows only valid sessions

3. **Proxying**

   * Intercepts requests and forwards them
   * Can filter content

4. **Network Address Translation (NAT)**

   * Hides internal IP addresses

---

## Common Firewall Rules (Exam-Focused)

* **Allow** or **deny** specific ports (e.g., HTTP 80, HTTPS 443)
* Restrict access to certain IP addresses
* Enable logging for monitoring

---

## Firewall vs Router vs Switch (Quick Comparison)

| Device   | Primary Function                 | OSI Layer |
| -------- | -------------------------------- | --------- |
| Firewall | Network security                 | L3–L7     |
| Router   | Forward packets between networks | L3        |
| Switch   | Forward frames within LAN        | L2        |

---

## Common Firewall Problems

* Blocked legitimate traffic
* Misconfigured rules
* VPN connection fails
* Unauthorized access due to weak rules

---

## Exam Tips

* Know **firewall types and OSI layers**
* Understand **packet filtering vs stateful inspection vs proxy**
* Be able to identify **firewall in troubleshooting scenarios**

---

## One-Line Summary

👉 **Firewall monitors and controls network traffic to protect against unauthorized access and threats**

