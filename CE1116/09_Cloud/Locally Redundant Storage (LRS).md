---
Last modification: 2025-08-08 09:06
tags:
  - Cloud
Tema: Development Process
---


## 📚 Idea/Concept 

Locally Redundant Storage (LRS) is a cloud storage redundancy model in which data is replicated multiple times within a single physical datacenter or availability zone. Its purpose is to ensure durability against localized hardware failures such as disk corruption, server outages, or even rack-level faults. Because all replicas remain within the same facility, LRS provides the lowest latency and highest performance of the redundancy options, making it suitable for workloads that require fast access to data and do not need protection against broader regional or zonal failures. Unlike Zone-Redundant Storage (ZRS), LRS does not replicate data across multiple availability zones; therefore, it offers the lowest geographic protection but the best efficiency and speed. This places LRS at the foundational level of the redundancy hierarchy (LRS < ZRS < GRS).
## 📌 Key points (Optional)
- LRS keeps all replicas inside one datacenter or availability zone, protecting against failures at the disk, server, or rack level.
- By storing all copies locally, LRS offers the fastest access times but provides no protection against zone-wide or regional outages.

## 🔗 Connections
- [[Zone-Redundant Storage (ZRS)]]
- [[Geo-Redundant Storage (GRS)]]
- [[IaaS vs PaaS vs SaaS]]