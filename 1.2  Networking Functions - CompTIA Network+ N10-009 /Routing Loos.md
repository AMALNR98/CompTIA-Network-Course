# Routing Loops

**CompTIA Network+ (N10-009)**

## What is a Routing Loop?

A **routing loop** occurs when a packet is **continuously forwarded between routers** because of **incorrect routing table entries** or misconfigured routing protocols.

📌 Think: **Packet stuck in a loop, never reaches its destination**

---

## OSI Layer

* **Layer 3 (Network Layer)** – Involves IP packet forwarding

---

## How Routing Loops Happen

1. Router A forwards a packet to Router B
2. Router B sends it to Router C
3. Router C mistakenly sends it back to Router A
4. The packet keeps looping indefinitely

---

## Effects of Routing Loops

* **Network congestion** – Unnecessary traffic consumes bandwidth
* **High CPU usage** – Routers process repeated packets
* **Packet loss** – Data never reaches its destination
* **Potential downtime** – May affect network performance

---

## Prevention Techniques

* **Time to Live (TTL):** Packet discarded if TTL reaches 0
* **Split Horizon:** Router does not advertise a route back to the interface it came from
* **Route Poisoning:** Mark invalid routes with an infinite metric
* **Hold-Down Timers:** Prevents routers from using unstable routes too soon
* **Use of modern routing protocols:** E.g., OSPF, EIGRP handle loops better

---

## Exam Tips

* Always associate **routing loops → Layer 3 → TTL, split horizon, route poisoning**
* Often appears in **scenario questions**: “Why does traffic never reach destination?” → Answer: **Routing loop**
* Know **effects and prevention mechanisms**

---

## One-Line Summary

👉 **A routing loop is a network condition where a packet circulates endlessly due to incorrect routing, prevented by TTL, split horizon, and route poisoning**

---

