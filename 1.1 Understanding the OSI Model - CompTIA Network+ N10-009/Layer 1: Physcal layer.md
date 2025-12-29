# Physical Layer (Layer 1)

**CompTIA Network+ (N10-009)**

## What is the Physical Layer?

The **Physical Layer** is the **lowest layer** of the OSI Model.
It is responsible for **sending raw bits (0s and 1s)** from one device to another **over a physical medium**.

📌 This layer deals with **hardware, signals, and media** — not data meaning.

---

## Main Responsibilities of the Physical Layer

* Transmission of **bits**
* Defines **cables, connectors, and signaling**
* Controls **voltage levels**
* Defines **data rates**
* Specifies **physical topology**

👉 No error detection, no addressing, no protocols

---

## What the Physical Layer DOES

✔ Converts data into **electrical, optical, or radio signals**
✔ Determines **how bits are represented**
✔ Handles **distance limitations**
✔ Defines **pin layouts & cable standards**

---

## What the Physical Layer DOES NOT Do

✘ No MAC addresses
✘ No IP addresses
✘ No encryption
✘ No error correction

📌 These belong to higher layers

---

## Physical Media Types

### 1. Copper Cables

Uses **electrical signals**

#### a) Twisted Pair Cable

* **UTP (Unshielded Twisted Pair)** – Most common
* **STP (Shielded Twisted Pair)** – Better noise protection

**Categories (important for exam):**

| Cable | Speed   | Distance |
| ----- | ------- | -------- |
| Cat5e | 1 Gbps  | 100 m    |
| Cat6  | 10 Gbps | 55 m     |
| Cat6a | 10 Gbps | 100 m    |

📌 **Max distance: 100 meters**

---

#### b) Coaxial Cable

* Used in cable internet
* Better shielding than twisted pair

Examples:

* RG-6
* RG-59

---

### 2. Fiber Optic Cables

Uses **light signals**

#### a) Single-Mode Fiber (SMF)

* Long distance
* Small core
* Used by ISPs

#### b) Multi-Mode Fiber (MMF)

* Short distance
* Larger core
* Used in LANs

📌 **Immune to EMI**

---

### 3. Wireless Media

Uses **radio waves**

Examples:

* Wi-Fi
* Bluetooth
* Cellular

📌 Still considered **Layer 1**

---

## Physical Layer Devices

| Device              | Description               |
| ------------------- | ------------------------- |
| Hub                 | Sends data to all ports   |
| Repeater            | Regenerates signal        |
| Modem               | Converts digital ↔ analog |
| NIC (Physical part) | Network Interface Card    |
| Cables & Connectors | RJ-45, Fiber connectors   |

📌 **Switches & Routers are NOT Layer 1 devices**

---

## Signaling Types

* **Electrical** (Copper)
* **Optical** (Fiber)
* **Radio** (Wireless)

---

## Common Physical Layer Problems (Exam-Focused)

* Cable unplugged
* Broken cable
* Incorrect cable type
* Interference (EMI)
* Signal attenuation

📌 Troubleshooting always starts at **Layer 1**

---

## Quick Exam Scenarios

🔹 *No link light on switch* → **Layer 1 issue**
🔹 *Damaged fiber cable* → **Layer 1**
🔹 *Wrong cable category* → **Layer 1**

---

## Physical Layer Keywords (Memorize)

* Bits
* Voltage
* Signals
* Media
* Cable
* Distance
* Bandwidth

---

## One-Line Summary (Very Important)

👉 **Layer 1 moves raw bits across physical media**

---

