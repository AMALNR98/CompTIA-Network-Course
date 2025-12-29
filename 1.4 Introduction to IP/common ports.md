# Common Network Ports & Protocols

**CompTIA Network+ (N10-009)**

---

## 1. FTP

**Full Form:** File Transfer Protocol
**Port:** TCP 21 (control), TCP 20 (data – active mode)

**What it does:**

* Transfers files between client and server

**Explanation:**
FTP allows uploading and downloading files but **does NOT encrypt data**.

📌 **Exam Tip:** FTP is **insecure**

---

## 2. SSH

**Full Form:** Secure Shell
**Port:** TCP 22

**What it does:**

* Secure remote login and command execution

**Explanation:**
Encrypted replacement for Telnet, used for server administration.

📌 **Exam Tip:** Secure remote access

---

## 3. Secure FTP (SFTP / FTPS)

### SFTP

**Full Form:** SSH File Transfer Protocol
**Port:** TCP 22

### FTPS

**Full Form:** FTP Secure
**Port:** TCP 990 (implicit)

**What it does:**

* Secure file transfer

**Explanation:**
SFTP uses SSH encryption; FTPS uses SSL/TLS.

📌 **Exam Tip:** SFTP ≠ FTP + SSL (it’s over SSH)

---

## 4. Telnet

**Full Form:** Telecommunication Network
**Port:** TCP 23

**What it does:**

* Remote command-line access

**Explanation:**
Sends data in **plain text** (insecure).

📌 **Exam Tip:** Replaced by SSH

---

## 5. SMTP

**Full Form:** Simple Mail Transfer Protocol
**Port:** TCP 25, 587 (secure), 465 (SSL)

**What it does:**

* Sends email between servers

**Explanation:**
SMTP is used for **sending mail**, not receiving.

---

## 6. DNS

**Full Form:** Domain Name System
**Port:** UDP 53 (queries), TCP 53 (zone transfers)

**What it does:**

* Converts domain names to IP addresses

**Explanation:**
Example: google.com → 142.250.x.x

---

## 7. DHCP

**Full Form:** Dynamic Host Configuration Protocol
**Port:** UDP 67 (server), UDP 68 (client)

**What it does:**

* Automatically assigns IP addresses

**Explanation:**
Provides IP, subnet mask, gateway, and DNS.

📌 **Mnemonic:** **DORA** (Discover, Offer, Request, Acknowledge)

---

## 8. TFTP

**Full Form:** Trivial File Transfer Protocol
**Port:** UDP 69

**What it does:**

* Lightweight file transfer

**Explanation:**
Used for **network booting and device configs**; no authentication.

---

## 9. HTTP

**Full Form:** Hypertext Transfer Protocol
**Port:** TCP 80

**What it does:**

* Transfers web pages

**Explanation:**
Unencrypted web communication.

---

## 10. HTTPS

**Full Form:** Hypertext Transfer Protocol Secure
**Port:** TCP 443

**What it does:**

* Secure web communication

**Explanation:**
Uses SSL/TLS encryption.

📌 **Exam Tip:** HTTPS = HTTP + encryption

---

## 11. NTP

**Full Form:** Network Time Protocol
**Port:** UDP 123

**What it does:**

* Synchronizes system clocks

**Explanation:**
Critical for logs, security, and authentication.

---

## 12. SNMP

**Full Form:** Simple Network Management Protocol
**Port:** UDP 161 (queries), UDP 162 (traps)

**What it does:**

* Monitors and manages network devices

**Explanation:**
Used by NMS tools to collect stats and alerts.

---

## 13. LDAP / LDAPS

### LDAP

**Full Form:** Lightweight Directory Access Protocol
**Port:** TCP 389

### LDAPS

**Port:** TCP 636

**What it does:**

* User authentication and directory services

**Explanation:**
Used by Active Directory for user and device management.

---

## 14. SMB

**Full Form:** Server Message Block
**Port:** TCP 445

**What it does:**

* File and printer sharing

**Explanation:**
Used in Windows networks.

---

## 15. SYSLOG

**Full Form:** System Logging Protocol
**Port:** UDP 514

**What it does:**

* Collects logs from network devices

**Explanation:**
Centralized logging for troubleshooting and security.

---

## 16. DATABASE (Common DB Ports)

| Database      | Port     |
| ------------- | -------- |
| MySQL         | TCP 3306 |
| PostgreSQL    | TCP 5432 |
| Microsoft SQL | TCP 1433 |
| Oracle DB     | TCP 1521 |

**What it does:**

* Database communication between client and server

---

## 17. RDP

**Full Form:** Remote Desktop Protocol
**Port:** TCP 3389

**What it does:**

* Remote graphical desktop access

**Explanation:**
Used for Windows remote administration.

---

## 18. SIP

**Full Form:** Session Initiation Protocol
**Port:** UDP/TCP 5060, TLS 5061

**What it does:**

* Establishes VoIP calls

**Explanation:**
Used for call setup, teardown, and signaling.

---

## Quick Exam Memory Table

| Protocol | Port    |
| -------- | ------- |
| FTP      | 21      |
| SSH      | 22      |
| Telnet   | 23      |
| SMTP     | 25      |
| DNS      | 53      |
| DHCP     | 67/68   |
| TFTP     | 69      |
| HTTP     | 80      |
| HTTPS    | 443     |
| NTP      | 123     |
| SNMP     | 161/162 |
| LDAP     | 389     |
| LDAPS    | 636     |
| SMB      | 445     |
| RDP      | 3389    |

---

## One-Line Summary

👉 **Network ports and protocols define how devices communicate, what service is used, and whether communication is secure or insecure**

---

