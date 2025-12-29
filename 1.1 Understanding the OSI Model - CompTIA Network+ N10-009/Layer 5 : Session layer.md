# Session Layer (Layer 5)

**CompTIA Network+ (N10-009)**

## What is the Session Layer?

The **Session Layer** is responsible for **establishing, managing, and terminating communication sessions** between applications on different devices.

📌 Think of it as the **conversation controller** between two systems.

---

## Main Responsibilities of Layer 5

* **Session establishment**
* **Session maintenance**
* **Session termination**
* **Session synchronization**
* **Dialog control** (who talks and when)

---

## What is a Session?

A **session** is a **logical connection** between two applications for the duration of communication.

Example:

* Logging into a remote server
* Accessing a file server
* Database connection

📌 Session ≠ TCP connection (exam trap)

---

## Key Functions Explained

### 1. Session Establishment

* Starts communication
* Sets session parameters

---

### 2. Session Maintenance

* Keeps session active
* Handles checkpoints
* Allows recovery after interruption

📌 Important for long data transfers

---

### 3. Session Termination

* Gracefully closes communication
* Frees resources

---

### 4. Dialog Control

* **Half-duplex** or **Full-duplex**
* Controls direction of data flow

---

### 5. Synchronization

* Adds **checkpoints**
* Allows session resume instead of restart

---

## Session Layer Protocols & Examples

* **NetBIOS Session Service**
* **RPC (Remote Procedure Call)**
* **SMB session management**

📌 Network+ focuses more on **concepts** than protocol details here

---

## Session Layer vs Transport Layer

| Feature | Session (L5)    | Transport (L4) |
| ------- | --------------- | -------------- |
| Purpose | Manage sessions | Deliver data   |
| Focus   | Conversations   | Segments       |
| Example | Login session   | TCP connection |

📌 Session layer controls **when**, Transport controls **how**

---

## Common Session Layer Issues (Exam-Focused)

* Session timeout
* Authentication session drop
* Remote login disconnects

---

## Troubleshooting Examples

🔹 *User gets logged out repeatedly* → **Layer 5**
🔹 *Remote session drops but network is fine* → **Layer 5**
🔹 *File transfer resumes after interruption* → **Layer 5 function**

---

## Key Exam Takeaways

✔ Session start/stop = Layer 5
✔ Dialog control = Layer 5
✔ Session recovery = Layer 5
✔ Session ≠ TCP connection

---

## One-Line Summary

👉 **Layer 5 manages, controls, and maintains communication sessions**
