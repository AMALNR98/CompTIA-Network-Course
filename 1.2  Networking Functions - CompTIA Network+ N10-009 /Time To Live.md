# Time to Live (TTL)

**CompTIA Network+ (N10-009)**

## What is TTL?

**Time to Live (TTL)** is a value in a network packet that **limits the lifetime of the packet** to prevent it from circulating indefinitely in a network.

📌 Think: **TTL = Packet’s “expiration timer”**

---

## OSI Layer

* **Layer 3 (Network Layer)** – Part of the IP header

---

## How TTL Works

1. Each IP packet has a **TTL value** (usually in seconds or hops)
2. Every time the packet passes through a **router**, TTL is **decremented by 1**
3. If TTL reaches **0**, the packet is **discarded** and a **ICMP “Time Exceeded”** message may be sent to the sender

---

## Purpose of TTL

* **Prevent routing loops**
* **Limit unnecessary network traffic**
* **Assist in troubleshooting** (used in tools like `traceroute`)

---

## TTL in Action

* **Traceroute:** Sends packets with incrementing TTL values
* Routers respond with ICMP messages when TTL expires
* Helps identify **path and hops between source and destination**

---

## Common Exam Points

* TTL is part of **IP header**
* **Decreases by 1 at each hop**
* **Prevents infinite loops** in a network
* Tools like **ping and traceroute** use TTL for diagnostics

---

## One-Line Summary

👉 **TTL is a network packet field that limits how long a packet can live in a network, preventing routing loops and aiding troubleshooting**


