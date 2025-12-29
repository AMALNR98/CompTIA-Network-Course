# Virtual Private Network (VPN)  
**CompTIA Network+ (N10-009)**  

## What is a VPN?
A **Virtual Private Network (VPN)** is a technology that **creates a secure, encrypted connection over a public network (like the Internet)**, allowing remote users or offices to **access private network resources safely**.  

📌 Think: **VPN = Secure “tunnel” over the Internet**  

---

## OSI Layer
- Primarily operates at **Layer 3 (Network)**
- Encryption and tunneling may involve **Layer 2 (Data Link)** and **Layer 7 (Application)** depending on protocol  

---

## Main Functions
- **Encryption:** Protects data in transit  
- **Authentication:** Ensures only authorized users can connect  
- **Data Integrity:** Prevents data tampering  
- **Remote Access:** Allows employees to securely access corporate networks  
- **Site-to-Site Connectivity:** Connects multiple office networks over the Internet  

---

## Common VPN Protocols
| Protocol | Description | OSI Layer | Key Feature |
|---------|------------|-----------|-------------|
| **IPSec** | Encrypts IP traffic | 3 | Site-to-site & remote access |
| **SSL/TLS VPN** | Uses HTTPS for secure access | 7 | Clientless VPN via browser |
| **PPTP** | Older, less secure | 2/3 | Legacy support |
| **L2TP** | Tunnels over IPSec | 2/3 | More secure than PPTP |
| **IKEv2** | Modern VPN protocol | 3 | Fast reconnection, mobile-friendly |

---

## Types of VPN
1. **Remote Access VPN** – Individual users connect to corporate network from anywhere  
2. **Site-to-Site VPN** – Connects entire networks (branch offices) securely  
3. **Client-based VPN** – Requires software installed on user device  
4. **Clientless VPN** – Access via web browser (SSL VPN)  

---

## VPN vs. Direct Connection
| Feature | VPN | Direct Connection |
|---------|-----|-----------------|
| Security | Encrypted tunnel | May be unencrypted |
| Accessibility | Remote users | Local access only |
| Cost | Low (Internet-based) | High (leased lines) |
| Flexibility | High | Low |

---

## Common Exam Points
- VPN = **secure remote connectivity**  
- Know **IPSec vs SSL VPN** differences  
- Site-to-site vs remote access VPN scenarios  
- Layer 3 tunneling protocols are often tested  

---

## One-Line Summary
👉 **A VPN creates a secure, encrypted tunnel over the Internet, enabling private network access for remote users or sites**  

---
