Here’s a **clear, exam-friendly note** on **IDS and IPS** for **CompTIA Network+ N10-009**.

---

# IDS and IPS

**CompTIA Network+ (N10-009)**

## What are IDS and IPS?

* **IDS (Intrusion Detection System):** Monitors network traffic and **alerts** on suspicious activity.
* **IPS (Intrusion Prevention System):** Monitors traffic **and blocks** malicious activity in real-time.

📌 Think: **IDS = Alarm**, **IPS = Alarm + Blocker**

---

## OSI Layer

* Typically operate at **Layer 3 (Network) and Layer 4 (Transport)**
* Some Next-Generation IDS/IPS inspect **Layer 7 (Application)** traffic

---

## Main Responsibilities

### IDS

* Monitors network for suspicious behavior
* Sends **alerts/logs** to administrator
* Passive; does **not block traffic**
* Types:

  * **Network-based (NIDS)** – Monitors network traffic
  * **Host-based (HIDS)** – Monitors individual devices

### IPS

* Monitors network **actively**
* Blocks or drops malicious traffic
* Can prevent attacks automatically
* Often integrated with firewalls

---

## IDS vs IPS (Quick Comparison)

| Feature        | IDS                   | IPS                               |
| -------------- | --------------------- | --------------------------------- |
| Action         | Detects & alerts      | Detects & blocks                  |
| Network impact | Passive               | Inline, may affect traffic        |
| Placement      | Out-of-band           | Inline                            |
| Example        | Alert email on attack | Drop packet from malicious source |

---

## Detection Methods

1. **Signature-based**

   * Matches known attack patterns
   * Fast, low false positives
   * Cannot detect new attacks

2. **Anomaly-based**

   * Detects unusual traffic patterns
   * Can detect new attacks
   * May produce false positives

3. **Behavior-based**

   * Monitors expected behavior and flags deviations

---

## Deployment

* **Inline (IPS)** – Traffic passes through device
* **Passive/Out-of-band (IDS)** – Monitors traffic via mirror/port span

---

## Common Use Cases

* Detect network scans or probes
* Block brute-force attacks
* Prevent malware propagation
* Monitor internal and external threats

---

## Exam Tips

* Remember: **IDS alerts, IPS blocks**
* NIDS vs HIDS distinction is often tested
* Signature vs anomaly detection differences
* Know **placement: inline vs passive**

---

## One-Line Summary

👉 **IDS detects malicious activity and alerts, while IPS detects and actively blocks threats in real-time**

---

If you want, next I can cover **Access Points (APs), Hub, and Repeater** together in one **exam-ready note**.

Do you want me to do that?
