# Virtual Network (VNet)

**CompTIA Network+ (N10-009)**

## What is a Virtual Network?

A **Virtual Network (VNet)** is a **software-defined network that exists within a cloud environment or virtualized infrastructure**, allowing devices and resources to communicate **as if they were on a physical network**.

📌 Think: **VNet = Network inside a cloud or hypervisor, fully controlled via software**

---

## OSI Layer

* Primarily **Layer 2 (Data Link) and Layer 3 (Network)**
* Layer 4/7 features possible with virtual appliances (firewalls, load balancers)

---

## Key Functions

1. **Isolation:** Segments network traffic between virtual machines (VMs) or tenants
2. **Subnetting:** Allows logical separation of resources within the VNet
3. **Routing:** Supports virtual routing tables for traffic management
4. **Security:** Implements **virtual firewalls, NSGs (Network Security Groups), VPN gateways**
5. **Connectivity:** Connects VNets to on-premises networks or other VNets via VPN or peering

---

## Types of Virtual Networks

| Type                        | Description                                                              |
| --------------------------- | ------------------------------------------------------------------------ |
| **Cloud VNet**              | Virtual networks in public cloud (Azure VNet, AWS VPC)                   |
| **Overlay Network**         | Software-defined network on top of physical network (VXLAN, GRE tunnels) |
| **Tenant/Isolated Network** | Segregates resources per user or tenant in multi-tenant cloud            |

---

## VNet vs Physical Network

| Feature      | VNet                         | Physical Network            |
| ------------ | ---------------------------- | --------------------------- |
| Deployment   | Software-defined             | Hardware-based              |
| Flexibility  | High, scalable on-demand     | Limited by physical devices |
| Security     | Virtual NSGs, firewalls      | Physical firewalls, VLANs   |
| Connectivity | VPN, peering, cloud gateways | Cables, routers, switches   |

---

## Common Use Cases

* Connect VMs in a cloud environment
* Isolate production, development, and testing networks
* Hybrid cloud connections with on-premises networks
* Multi-tenant cloud hosting environments

---

## Exam Tips

* Virtual networks are **software-defined Layer 2/3 networks**
* Often paired with **cloud services, VNFs, and VPNs**
* Know **VNet isolation, subnetting, and security features**
* Scenario questions may involve **hybrid network connectivity**

---

## One-Line Summary

👉 **A Virtual Network is a software-defined network that provides isolated, secure, and scalable connectivity for virtual resources in cloud or virtualized environments**

---

