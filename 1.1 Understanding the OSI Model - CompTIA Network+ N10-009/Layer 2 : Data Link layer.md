# Data Link Layer (Layer 2)
**CompTIA Network+ (N10-009)**

## What is the Data Link Layer?
The **Data Link Layer** is responsible for **node-to-node delivery** of data on the **same network**.  
It ensures data is transferred **reliably across a physical link** using **frames and MAC addresses**.

📌 Works directly above the **Physical Layer (Layer 1)**

---

## Main Responsibilities of Layer 2
- **Framing** (encapsulates data into frames)
- **Physical (MAC) addressing**
- **Error detection**
- **Flow control**
- **Media access control**

---

## Data Link Layer Sub-Layers
Layer 2 is divided into **two sublayers**:

### 1. Logical Link Control (LLC)
- Error checking
- Flow control
- Identifies Layer 3 protocol (IPv4, IPv6)

### 2. Media Access Control (MAC)
- Handles **MAC addresses**
- Controls access to physical media
- Responsible for frame delivery

📌 **MAC address belongs here**

---

## MAC Address (Very Important)
A **MAC address** is a **unique 48-bit physical address** assigned to a NIC.

Example:
```
00:1A:2B:3C:4D:5E
```

- First 24 bits → **Vendor ID (OUI)**
- Last 24 bits → **Device ID**

📌 MAC address = **Layer 2**
📌 IP address = **Layer 3**

---

## Framing Process
1. Data received from Layer 3
2. Adds:
   - Source MAC
   - Destination MAC
   - Error-checking info (FCS)
3. Sends frame to Physical Layer

---

## Error Detection
- Uses **Frame Check Sequence (FCS)**
- Based on **CRC (Cyclic Redundancy Check)**
- Detects corrupted frames

📌 Error detection ≠ error correction

---

## Layer 2 Devices

| Device | Function |
|------|---------|
| Switch | Forwards frames using MAC table |
| Bridge | Connects network segments |
| NIC | Provides MAC address |

📌 **Switch = Layer 2 device (important exam point)**

---

## Ethernet (Most Important Layer 2 Technology)
Ethernet defines:
- Frame format
- MAC addressing
- Media access method

### Ethernet Frame Fields (Basic)
- Destination MAC
- Source MAC
- Type
- Data
- FCS

---

## ARP (Address Resolution Protocol)
**ARP maps IP address → MAC address**

Example:
- IP: 192.168.1.10
- MAC: 00:1A:2B:3C:4D:5E

📌 ARP works between **Layer 2 & Layer 3**
📌 Heavily tested in Network+

---

## VLANs (Virtual LANs)
- Logical separation of networks
- Reduces broadcast traffic
- Improves security

📌 VLANs operate at **Layer 2**

---

## Broadcast, Multicast & Unicast
- **Unicast:** One-to-one
- **Broadcast:** One-to-all (FF:FF:FF:FF:FF:FF)
- **Multicast:** One-to-many

📌 Broadcasts stay within Layer 2 network

---

## Common Layer 2 Problems (Exam-Focused)
- Wrong MAC address
- Switch misconfiguration
- VLAN mismatch
- ARP issues

---

## Troubleshooting Clues
| Symptom | Layer |
|------|------|
| No communication in same LAN | Layer 2 |
| MAC address conflict | Layer 2 |
| Switch issue | Layer 2 |

---

## Key Exam Takeaways
✔ MAC addressing = Layer 2  
✔ Switches operate at Layer 2  
✔ Frames belong to Layer 2  
✔ VLANs & ARP are Layer 2 concepts  

---

## One-Line Summary
👉 **Layer 2 delivers frames using MAC addresses within the same network**

