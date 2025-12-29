# Load Balancer

**CompTIA Network+ (N10-009)**

## What is a Load Balancer?

A **load balancer** is a network device or software that **distributes incoming network traffic across multiple servers** to ensure **high availability and performance**.

📌 Think: **Load Balancer = Traffic Manager for servers**

---

## OSI Layer

* Can operate at multiple layers:

  * **Layer 4 (Transport):** TCP/UDP traffic balancing
  * **Layer 7 (Application):** Application-aware balancing (HTTP, HTTPS, DNS)

---

## Main Responsibilities

* Distributes client requests across multiple servers
* Ensures **no single server is overloaded**
* Increases **redundancy and fault tolerance**
* Monitors **server health** and directs traffic accordingly
* Improves **response times and reliability**

---

## Types of Load Balancing

| Type                  | Description                                            | Example                            |
| --------------------- | ------------------------------------------------------ | ---------------------------------- |
| **Round Robin**       | Cycles requests evenly across servers                  | Simple web load balancing          |
| **Least Connections** | Sends request to server with fewest active connections | Web apps with variable traffic     |
| **IP Hash**           | Uses client IP to decide server                        | Sticky sessions                    |
| **Weighted**          | Servers get traffic based on capacity                  | Servers with different performance |

---

## Key Functions

1. **Traffic Distribution** – Evenly spread workload across servers
2. **Health Checks** – Ensures traffic is sent only to healthy servers
3. **High Availability** – Maintains uptime if one server fails
4. **Scalability** – Allows easy addition of servers

---

## Load Balancer vs Firewall vs Router

| Device        | Primary Function                 | OSI Layer |
| ------------- | -------------------------------- | --------- |
| Load Balancer | Distribute traffic               | L4/L7     |
| Router        | Forward packets between networks | L3        |
| Firewall      | Filter traffic based on rules    | L3–L7     |

---

## Common Use Cases

* Web servers for high-traffic websites
* Email servers (SMTP, IMAP)
* Database servers with multiple nodes
* Cloud service traffic management

---

## Exam Tips

* Layer 4 = Transport-based (TCP/UDP ports)
* Layer 7 = Application-based (HTTP/HTTPS)
* Know **traffic distribution methods** (Round Robin, Least Connections, IP Hash)
* Focus on **availability, redundancy, and scalability**

---

## One-Line Summary

👉 **Load balancer distributes network traffic across multiple servers to improve performance, availability, and reliability**

---

