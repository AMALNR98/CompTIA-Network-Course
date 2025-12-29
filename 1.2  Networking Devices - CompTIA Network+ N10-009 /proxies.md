# Proxy Server

**CompTIA Network+ (N10-009)**

## What is a Proxy Server?

A **proxy server** is an intermediary device that **receives client requests, processes them, and forwards them to the destination server**.

📌 Think: **Proxy = Middleman between client and internet**

---

## OSI Layer

* Primarily **Layer 7 (Application Layer)**
* Can inspect and filter traffic at **higher layers** (HTTP, HTTPS, FTP)

---

## Main Responsibilities

* **Request forwarding** – Sends client requests to servers
* **Content filtering** – Blocks malicious or inappropriate content
* **Caching** – Stores frequently accessed data to improve speed
* **Anonymity** – Hides client IP address from external servers
* **Security** – Works with firewalls to filter threats

---

## Types of Proxy Servers

| Type                  | Description                                             | Use Case                                 |
| --------------------- | ------------------------------------------------------- | ---------------------------------------- |
| **Forward Proxy**     | Forwards requests from internal clients to the internet | Access control, anonymity                |
| **Reverse Proxy**     | Receives requests from internet to internal servers     | Load balancing, security, SSL offloading |
| **Transparent Proxy** | Intercepts traffic without client configuration         | Content filtering, monitoring            |
| **Anonymous Proxy**   | Hides client IP from external server                    | Privacy, bypass restrictions             |
| **Caching Proxy**     | Stores frequently requested data                        | Reduce bandwidth usage, improve speed    |

---

## Proxy vs Firewall

| Feature            | Proxy                             | Firewall                           |
| ------------------ | --------------------------------- | ---------------------------------- |
| Primary Function   | Intermediary & content inspection | Traffic filtering & access control |
| OSI Layer          | L7                                | L3–L7                              |
| Traffic Visibility | Full request inspection           | Header/packet inspection           |
| Client IP Hiding   | Yes                               | No                                 |

---

## Common Use Cases

* Restrict web access in corporate networks
* Hide internal network topology from the internet
* Improve performance with cached web content
* Load balancing and SSL offloading (reverse proxy)

---

## Exam Tips

* **Forward proxy = client-side**
* **Reverse proxy = server-side**
* **Caching improves performance**
* Often paired with **firewalls or load balancers**

---

## One-Line Summary

👉 **A proxy server acts as an intermediary between clients and servers to provide security, anonymity, content filtering, and caching**

---
