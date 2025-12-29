# Transport Layer (Layer 4)

**CompTIA Network+ (N10-009)**

## What is the Transport Layer?

The **Transport Layer** is responsible for **end-to-end communication** between applications on different devices.

📌 It ensures data is delivered to the **correct application** using **port numbers**.

---

## Main Responsibilities of Layer 4

* **Segmentation & reassembly**
* **Port addressing**
* **Flow control**
* **Error control**
* **Reliable or unreliable delivery**

---

## Data Unit at Layer 4

| Layer       | Data Unit   |
| ----------- | ----------- |
| Layer 3     | Packet      |
| **Layer 4** | **Segment** |
| Layer 5–7   | Data        |

---

## Port Numbers (Very Important)

Ports identify **applications/services**.

### Port Ranges

| Range       | Name       | Example                |
| ----------- | ---------- | ---------------------- |
| 0–1023      | Well-known | HTTP (80), HTTPS (443) |
| 1024–49151  | Registered | MySQL (3306)           |
| 49152–65535 | Dynamic    | Client ports           |

📌 Port numbers = **Layer 4**

---

## Transport Layer Protocols

### 1. TCP (Transmission Control Protocol)

**Connection-oriented & reliable**

**Features:**

* 3-way handshake
* Acknowledgements
* Retransmission
* Flow control
* Error checking

**Used for:**

* HTTP / HTTPS
* FTP
* SMTP
* SSH

📌 Slower but reliable

---

### TCP 3-Way Handshake

1. **SYN**
2. **SYN-ACK**
3. **ACK**

📌 Frequently tested in Network+

---

### 2. UDP (User Datagram Protocol)

**Connectionless & unreliable**

**Features:**

* No handshake
* No acknowledgements
* Faster transmission

**Used for:**

* DNS
* VoIP
* Video streaming
* Online gaming

📌 Faster but no delivery guarantee

---

## TCP vs UDP (Must Memorize)

| Feature        | TCP        | UDP             |
| -------------- | ---------- | --------------- |
| Connection     | Yes        | No              |
| Reliability    | High       | Low             |
| Speed          | Slower     | Faster          |
| Error checking | Yes        | Minimal         |
| Use case       | Web, Email | Streaming, VoIP |

---

## Flow Control

* Prevents sender from overwhelming receiver
* Uses **window size**

📌 TCP feature

---

## Error Control

* Detects lost or corrupted segments
* Retransmits data

📌 TCP only

---

## Multiplexing & Demultiplexing

* **Multiplexing:** Multiple apps send data
* **Demultiplexing:** Correct app receives data

📌 Achieved using **port numbers**

---

## Common Layer 4 Problems (Exam-Focused)

* Wrong port blocked
* Firewall blocking TCP/UDP
* Application not reachable

---

## Troubleshooting Examples

🔹 *Website not loading but ping works* → **Layer 4**
🔹 *Firewall blocking port 443* → **Layer 4**
🔹 *VoIP delay* → **UDP issue (Layer 4)**

---

## Key Exam Takeaways

✔ Ports = Layer 4
✔ TCP & UDP = Layer 4
✔ Reliability vs speed questions
✔ 3-way handshake is important

---

## One-Line Summary

👉 **Layer 4 delivers data between applications using TCP or UDP and port numbers**

