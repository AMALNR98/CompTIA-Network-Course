# Domain Name System (DNS)

**CompTIA Network+ (N10-009)**

## What is DNS?

**Domain Name System (DNS)** is a network service that **translates human-readable domain names (like [www.example.com](http://www.example.com)) into IP addresses** and vice versa.

📌 Think: **DNS = Internet’s phonebook**

---

## OSI Layer

* Primarily **Layer 7 (Application Layer)**

---

## Key Functions

1. **Name Resolution:** Converts domain names to IP addresses
2. **Reverse Lookup:** Converts IP addresses back to domain names
3. **Load Distribution:** Distributes traffic among multiple servers (via multiple A records)
4. **Caching:** Reduces query times by storing recently resolved names
5. **Email Routing:** Supports MX records for mail delivery

---

## Common DNS Record Types

| Record    | Purpose                                     |
| --------- | ------------------------------------------- |
| **A**     | Maps hostname to IPv4 address               |
| **AAAA**  | Maps hostname to IPv6 address               |
| **CNAME** | Canonical name / alias for another hostname |
| **MX**    | Mail exchange server for domain             |
| **NS**    | Authoritative name servers for domain       |
| **PTR**   | Reverse lookup (IP → hostname)              |
| **SRV**   | Specifies service location                  |

---

## DNS Query Types

* **Recursive Query:** Client requests DNS server to resolve fully
* **Iterative Query:** Server responds with best info it has or refers to another server

---

## DNS Components

* **Root Servers:** Top-level DNS servers
* **TLD Servers:** Top-level domain servers (.com, .org, .net)
* **Authoritative Name Servers:** Store actual domain records
* **Resolvers:** Client-side components that request DNS lookups

---

## Common Exam Points

* DNS = **Layer 7 service**
* Know **A, AAAA, CNAME, MX, PTR, NS records**
* **Recursive vs iterative queries** may appear in scenario questions
* DNS caching helps **speed up subsequent lookups**

---

## DNS vs IP Addressing

| Feature        | DNS                    | IP Address                             |
| -------------- | ---------------------- | -------------------------------------- |
| Function       | Name resolution        | Network addressing                     |
| Layer          | 7                      | 3                                      |
| Human-friendly | Yes                    | No                                     |
| Dynamic        | Can change IP mappings | Fixed to devices (may change via DHCP) |

---

## One-Line Summary

👉 **DNS translates human-friendly domain names to IP addresses and supports reverse lookup, caching, and mail routing**

---
