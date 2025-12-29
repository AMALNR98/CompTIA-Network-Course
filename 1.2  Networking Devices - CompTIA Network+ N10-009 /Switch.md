# Switch  
**CompTIA Network+ (N10-009)**

## What is a Switch?
A **switch** is a network device that **connects multiple devices within a LAN** and **forwards frames based on MAC addresses**.  

📌 Think of it as the **intelligent hub** that only sends data where it’s needed.

---

## OSI Layer
- Primary: **Layer 2 (Data Link Layer)**
- Some switches (Layer 3 switches) can perform **routing** (Layer 3)

---

## Key Responsibilities
- **Forwarding frames** using MAC address table  
- **Filtering traffic** to reduce collisions  
- **Segmenting collision domains**  
- **VLAN support** (logical separation of networks)  
- Can provide **PoE (Power over Ethernet)** to devices like phones and APs  

---

## How Switch Works
1. Receives a frame
2. Reads the **destination MAC address**
3. Looks up MAC in **MAC address table**
4. Forwards frame to correct port (unicast)  
5. Broadcasts only if unknown MAC  

📌 **Reduces unnecessary traffic compared to hubs**

---

## MAC Address Table
- Stores **MAC addresses learned on each port**  
- Helps switch **forward frames accurately**  
- Updates dynamically as devices connect  

---

## Types of Switches
| Type | Function |
|------|---------|
| Unmanaged | Plug-and-play, no configuration |
| Managed | Configurable, supports VLANs, QoS, SNMP |
| Layer 3 Switch | Performs routing and switching |
| PoE Switch | Provides power to devices over Ethernet |

---

## VLANs (Virtual LANs)
- Logical separation of devices within a LAN  
- Reduces broadcast traffic  
- Increases security  
- Tagging methods: **802.1Q** (exam-relevant)  

📌 VLAN = Layer 2 concept  
📌 Layer 3 switch needed to route between VLANs

---

## Switch vs Hub vs Router (Quick Comparison)

| Feature | Switch | Hub | Router |
|---------|--------|-----|-------|
| OSI Layer | 2 | 1 | 3 |
| Forwarding | Frames (MAC) | Bits | Packets (IP) |
| Collision Domains | Per port | Single | N/A |
| Broadcast Domains | Single | Single | Each interface |

---

## Common Switch Problems
- MAC address table overflow  
- Misconfigured VLAN  
- Port security issues  
- Broadcast storms  

---

## Exam Tips
- Switch = **Layer 2, forwards frames by MAC**  
- VLANs and MAC address tables are key concepts  
- Layer 3 switches are **rarely tested in deep configuration**, focus on concept  
- Compare with hub and router for scenario questions  

---

## One-Line Summary
👉 **Switch connects devices in a LAN and forwards frames based on MAC addresses, reducing collisions and improving network efficiency**

---
