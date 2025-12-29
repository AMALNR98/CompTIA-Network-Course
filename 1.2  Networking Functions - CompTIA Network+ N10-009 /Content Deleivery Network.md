# Content Delivery Network (CDN)

**CompTIA Network+ (N10-009)**

## What is a CDN?

A **Content Delivery Network (CDN)** is a **distributed network of servers** that delivers web content, videos, and other resources to users **based on their geographic location**, improving **speed, reliability, and availability**.

📌 Think: **CDN = Global caching network to make websites load faster**

---

## OSI Layer

* Operates primarily at **Layer 7 (Application Layer)**
* Deals with **HTTP/HTTPS traffic, caching, and web content delivery**

---

## Main Responsibilities

* **Reduce latency** – Serve content from the nearest server to the user
* **Load balancing** – Distribute traffic across multiple servers
* **Improve reliability** – Prevent single server overload or downtime
* **Offload origin servers** – Reduce load on the main web server
* **Security features** – DDoS mitigation, SSL termination, Web Application Firewall (WAF) integration

---

## Key Components

1. **Edge Servers:** Located close to end-users for faster delivery
2. **Origin Server:** Original source of content
3. **PoPs (Points of Presence):** Data centers hosting edge servers globally
4. **Caching Mechanisms:** Temporarily store frequently requested content

---

## Benefits

* Faster content delivery for users worldwide
* Scalable for high traffic spikes
* Reduces bandwidth consumption
* Protects against DDoS attacks

---

## Common Use Cases

* Streaming video services (Netflix, YouTube)
* Global websites (news portals, e-commerce sites)
* Software updates distribution
* Gaming platforms

---

## CDN vs Traditional Hosting

| Feature     | CDN                | Traditional Hosting       |
| ----------- | ------------------ | ------------------------- |
| Latency     | Low (edge servers) | High (origin server only) |
| Scalability | High               | Limited                   |
| Reliability | High               | Depends on single server  |
| Security    | Built-in features  | Needs separate solutions  |

---

## Exam Tips

* CDN is **Layer 7 (Application Layer)**
* Focus on **speed, reliability, load balancing, and security**
* Often asked in scenarios: *“How to reduce latency for global users?”* → Answer: **CDN**

---

## One-Line Summary

👉 **A CDN is a distributed network of servers that delivers content quickly, reliably, and securely to users based on their location**

---

