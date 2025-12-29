# Network Layer (Layer 3)

**CompTIA Network+ (N10-009)**

## What is the Network Layer?

The **Network Layer** is responsible for **logical addressing and routing**.
It decides **how data travels from one network to another network**.

📌 If data must leave the local network → **Layer 3 is involved**

---

## Main Responsibilities of Layer 3

* **Logical addressing (IP addresses)**
* **Routing packets between networks**
* **Path selection**
* **Packet forwarding**
* **Fragmentation & reassembly**

---

## Data Unit at Layer 3

| Layer       | Data Unit  |
| ----------- | ---------- |
| Layer 2     | Frame      |
| **Layer 3** | **Packet** |
| Layer 4     | Segment    |

📌 Network Layer works with **packets**

---

## Logical Addressing (IP Addressing)

### IPv4

* 32-bit address
* Example: `192.168.1.1`

### IPv6

* 128-bit address
* Example: `2001:db8::1`

📌 IP address = **Layer 3**
📌 MAC address = **Layer 2**

---

## Routing (Core Function)

Routing is the process of **choosing the best path** to reach the destination network.

### Routing Methods

* **Static routing** – manually configured
* **Dynamic routing** – automatic

📌 Network+ focuses more on **concepts** than deep router configuration

---

## Network Layer Devices

| Device            | Function                        |
| ----------------- | ------------------------------- |
| **Router**        | Routes packets between networks |
| Layer 3 Switch    | Switch + routing capability     |
| Firewall (partly) | Filters traffic by IP           |

📌 **Router = Layer 3 device (very important)**

---

## Network Layer Protocols

### 1. IP (Internet Protocol)

* Core protocol of Layer 3
* Provides logical addressing
* Best-effort delivery (no guarantee)

---

### 2. ICMP (Internet Control Message Protocol)

Used for:

* Error reporting
* Diagnostics

Examples:

* `ping`
* `traceroute`

📌 Ping not working → possible Layer 3 issue

---

### 3. IPsec

* Secure IP communication
* Encryption & authentication

📌 Security + IP = **Layer 3**

---

## Packet Fragmentation

Occurs when:

* Packet is **larger than MTU**

📌 IPv4 allows routers to fragment packets
📌 IPv6 does **not** allow router fragmentation

---

## Network Layer vs Data Link Layer

| Feature    | Layer 2       | Layer 3          |
| ---------- | ------------- | ---------------- |
| Addressing | MAC           | IP               |
| Scope      | Local network | Between networks |
| Device     | Switch        | Router           |
| Data unit  | Frame         | Packet           |

---

## Broadcast Domains

* **Routers break broadcast domains**
* Switches do **not**

📌 Very common exam question

---

## Common Layer 3 Problems (Exam-Focused)

* Incorrect IP address
* Wrong subnet mask
* Incorrect default gateway
* Routing issues

---

## Troubleshooting Examples

🔹 *Can access local devices but not internet* → **Layer 3**
🔹 *Wrong default gateway* → **Layer 3**
🔹 *Ping fails across networks* → **Layer 3**

---

## Key Exam Takeaways

✔ IP addressing = Layer 3
✔ Routing = Layer 3
✔ Routers operate at Layer 3
✔ ICMP & IPsec belong to Layer 3

---

## One-Line Summary

👉 **Layer 3 moves packets between networks using IP addresses**

