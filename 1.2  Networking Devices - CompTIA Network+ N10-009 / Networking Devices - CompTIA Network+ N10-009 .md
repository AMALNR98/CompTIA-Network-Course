# Networking Devices

**CompTIA Network+ (N10-009)**

Networking devices are **hardware components** used to **connect, manage, and secure networks**.

📌 Important for exam: Know **device functions, OSI layer, and use cases**.

---

## 1. **Hub**

* **Function:** Connects multiple devices in a LAN
* **OSI Layer:** Layer 1 (Physical Layer)
* **Key Features:**

  * Broadcasts data to all ports
  * No intelligence; cannot filter traffic
  * Used rarely today
* **Exam Tip:** If “all devices receive the same signal,” think **Hub**

---

## 2. **Switch**

* **Function:** Connects devices in a LAN and forwards frames based on MAC addresses
* **OSI Layer:** Layer 2 (Data Link Layer)
* **Key Features:**

  * Maintains MAC address table
  * Reduces collisions
  * Supports VLANs
  * Some switches have Layer 3 routing (Layer 3 switch)
* **Exam Tip:** “Forwarding frames based on MAC” → **Switch**

---

## 3. **Router**

* **Function:** Routes packets between different networks
* **OSI Layer:** Layer 3 (Network Layer)
* **Key Features:**

  * Uses IP addresses for routing
  * Connects LAN to WAN / Internet
  * Supports NAT, firewall functions
* **Exam Tip:** “Connects different networks” → **Router**

---

## 4. **Modem**

* **Function:** Converts digital signals to analog and vice versa
* **OSI Layer:** Layer 1 (Physical Layer)
* **Key Features:**

  * Used for Internet connection over phone lines or cable
  * DSL, Cable, Fiber modems
* **Exam Tip:** “Digital ↔ Analog conversion” → **Modem**

---

## 5. **Access Point (AP)**

* **Function:** Provides wireless access to wired LAN
* **OSI Layer:** Layer 2 (Data Link)
* **Key Features:**

  * Connects Wi-Fi devices
  * Extends network coverage
  * Can support VLANs
* **Exam Tip:** “Wireless connection for wired LAN” → **AP**

---

## 6. **Firewall**

* **Function:** Controls network traffic based on security rules
* **OSI Layer:** Layer 3 / Layer 4 (can also operate at Layer 7 in application firewall)
* **Key Features:**

  * Packet filtering
  * Stateful inspection
  * Protects internal network from external threats
* **Exam Tip:** “Blocks or allows traffic based on rules” → **Firewall**

---

## 7. **Repeater**

* **Function:** Regenerates and amplifies signals to extend network range
* **OSI Layer:** Layer 1 (Physical Layer)
* **Key Features:**

  * No intelligence; just boosts signal
* **Exam Tip:** “Extends network over long distance” → **Repeater**

---

## 8. **Bridge**

* **Function:** Connects two LAN segments and filters traffic based on MAC addresses
* **OSI Layer:** Layer 2 (Data Link Layer)
* **Key Features:**

  * Reduces collision domains
  * Less common today (replaced by switches)

---

## 9. **Gateway**

* **Function:** Connects networks with different protocols
* **OSI Layer:** Layer 7 (Application Layer)
* **Key Features:**

  * Protocol conversion (e.g., TCP/IP ↔ SNA)
  * Often integrated in routers

---

## 10. **Load Balancer**

* **Function:** Distributes traffic across multiple servers
* **OSI Layer:** Layer 4 / Layer 7
* **Key Features:**

  * Ensures high availability
  * Improves performance
* **Exam Tip:** “Distributes traffic evenly across servers” → **Load Balancer**

---

## Quick OSI Layer Reference for Devices

| Device        | OSI Layer |
| ------------- | --------- |
| Hub           | 1         |
| Repeater      | 1         |
| Switch        | 2         |
| Bridge        | 2         |
| Router        | 3         |
| Firewall      | 3–7       |
| Gateway       | 7         |
| Access Point  | 2         |
| Load Balancer | 4–7       |
| Modem         | 1         |

---

## Exam Tips

* Always **associate device with its OSI layer**
* Memorize **purpose and function**
* Watch out for **scenario-based questions** (“Which device to use?”)


