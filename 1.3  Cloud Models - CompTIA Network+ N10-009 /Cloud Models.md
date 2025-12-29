# Cloud Models

**CompTIA Network+ (N10-009)**

Cloud models define **how cloud resources are deployed, managed, and shared** across organizations.

📌 Think: **Cloud model = Who owns, manages, and who can use the cloud resources**

---

## 1. **Deployment Models**

| Model               | Description                                                                                              | Example                                            | Key Features                                                                |
| ------------------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | --------------------------------------------------------------------------- |
| **Public Cloud**    | Cloud infrastructure is owned and operated by a third-party provider and shared among multiple customers | AWS, Azure, Google Cloud                           | Cost-effective, scalable, managed by provider, accessible over the internet |
| **Private Cloud**   | Dedicated cloud infrastructure for a single organization                                                 | VMware private cloud, Azure Stack                  | High security, customizable, managed internally or by a provider            |
| **Hybrid Cloud**    | Combines public and private clouds                                                                       | Office data in private cloud, apps in public cloud | Flexibility, scalability, sensitive data kept private                       |
| **Community Cloud** | Shared cloud among organizations with similar requirements                                               | Government, healthcare consortiums                 | Shared infrastructure, compliance-focused, cost-sharing                     |

---

## 2. **Service Models**

| Model                                         | Description                                                             | Examples                              | OSI Layer Interaction        |
| --------------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------- | ---------------------------- |
| **IaaS (Infrastructure as a Service)**        | Provides virtualized computing resources (servers, storage, networking) | AWS EC2, Azure VMs                    | Layer 3–4 (network, routing) |
| **PaaS (Platform as a Service)**              | Provides platforms for app development and deployment                   | Google App Engine, Azure App Services | Layer 7 (application)        |
| **SaaS (Software as a Service)**              | Provides ready-to-use applications                                      | Office 365, Salesforce                | Layer 7                      |
| **FaaS (Function as a Service / Serverless)** | Executes event-driven functions without managing servers                | AWS Lambda, Azure Functions           | Layer 7                      |

---

## 3. **Key Considerations in Cloud Design**

1. **Scalability:** Ability to expand or shrink resources based on demand
2. **Redundancy & High Availability:** Avoid single points of failure
3. **Security:** Encryption, identity and access management (IAM), firewall rules
4. **Cost Management:** Pay-as-you-go pricing, monitoring resource usage
5. **Compliance:** Ensure regulatory requirements (HIPAA, GDPR, etc.)

---

## 4. **Cloud Connectivity**

* **VPN:** Secure encrypted connection from on-premises to cloud
* **Direct Connect / ExpressRoute:** Dedicated private connection to cloud provider
* **Hybrid Networking:** Integration of on-premises and cloud resources

---

## 5. **Advantages of Cloud Models**

* Reduced CAPEX and hardware management
* Quick provisioning of resources
* Global accessibility
* Flexible scaling

---

## 6. **Challenges**

* Vendor lock-in
* Data security and compliance
* Latency issues for remote users
* Complexity in hybrid/multi-cloud setups

---

## Exam Tips

* Know **deployment vs service models**
* Public vs private vs hybrid vs community
* IaaS vs PaaS vs SaaS vs FaaS differences
* Cloud connectivity methods: VPN, Direct Connect, hybrid networking

---

## One-Line Summary

👉 **Cloud models define how cloud resources are deployed and consumed, with deployment models specifying ownership and sharing, and service models specifying the type of service offered (IaaS, PaaS, SaaS, FaaS)**

---
