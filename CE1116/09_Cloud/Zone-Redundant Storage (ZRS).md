---
Last modification: 2025-08-08 09:06
tags:
  - Cloud
Tema: Development Process
---


## 📚 Idea/Concept 

Zone-Redundant Storage (ZRS) is a cloud storage redundancy model in which data is synchronously replicated across three physically separate availability zones within the same region. Each zone functions as an independent datacenter equipped with its own power, cooling, and networking, ensuring that data remains available even if an entire zone experiences an outage. By distributing replicas across multiple isolated zones, ZRS provides significantly higher durability and availability than Locally Redundant Storage (LRS), which keeps all copies within a single facility. However, ZRS may introduce slightly higher latency due to cross-zone replication and communication, representing a trade-off between enhanced resilience and performance. This model is designed for workloads that require strong regional high availability and protection against datacenter-level failures without the need for cross-region disaster recovery.
## 📌 Key points (Optional)
- ZRS replicates data synchronously across three separate availability zones, ensuring resilience against full datacenter failures.
- ZRS offers stronger protection than LRS but may introduce higher latency due to cross-zone data distribution.

## 🔗 Connections
- [[Locally Redundant Storage (LRS)]]
- [[Geo-Redundant Storage (GRS)]]
- [[Hybrid Cloud]]