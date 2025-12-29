# Quality of Service (QoS)

**CompTIA Network+ (N10-009)**

## What is QoS?

**Quality of Service (QoS)** is a networking technique that **prioritizes certain types of traffic over others** to ensure **reliable performance for critical applications**.

📌 Think: **QoS = Traffic priority manager**

---

## OSI Layer

* Operates mainly at **Layer 3 (Network)** and **Layer 4 (Transport)**
* Some implementations consider **Layer 2 for VLAN tagging**

---

## Main Functions

* **Traffic Prioritization:** Assign higher priority to critical traffic (e.g., voice, video)
* **Bandwidth Management:** Allocate specific bandwidth for certain applications
* **Latency Reduction:** Reduce delays for time-sensitive traffic
* **Jitter Control:** Ensure smooth delivery of voice/video streams
* **Packet Loss Prevention:** Minimize dropped packets for important traffic

---

## Common QoS Techniques

| Technique                    | Description                                                              |
| ---------------------------- | ------------------------------------------------------------------------ |
| **Traffic Shaping**          | Delays lower-priority traffic to prevent congestion                      |
| **Traffic Policing**         | Drops traffic exceeding set limits                                       |
| **Classification & Marking** | Identifies traffic type and assigns priority (DSCP, IP precedence)       |
| **Queue Management**         | Uses multiple queues to prioritize packets (FIFO, weighted fair queuing) |

---

## QoS Prioritization Example

* **High priority:** VoIP, video conferencing
* **Medium priority:** Critical business applications
* **Low priority:** Email, file downloads, bulk data

---

## QoS in Practice

* **Routers & Switches** enforce QoS rules
* Often combined with **VLANs** for segmentation
* Common in **VoIP, video streaming, and real-time applications**

---

## QoS vs Traffic Management

| Feature | QoS                         | Traffic Management            |
| ------- | --------------------------- | ----------------------------- |
| Purpose | Prioritize critical traffic | Optimize overall network flow |
| Layer   | 3–4                         | 2–7                           |
| Focus   | Application performance     | Bandwidth efficiency          |

---

## Exam Tips

* Know **purpose of QoS**: reduce latency, jitter, packet loss for critical apps
* Remember **Layer 3/4 focus** and common techniques: shaping, policing, DSCP
* Scenario-based questions often ask: *“Which technique ensures VoIP quality?”* → Answer: **QoS**

---

## One-Line Summary

👉 **QoS prioritizes important network traffic to ensure reliable performance for time-sensitive applications like voice and video**

---

