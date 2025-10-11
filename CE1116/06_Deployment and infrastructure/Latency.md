---
Last Modification: 2025-08-08 09:09
tags:
  - Sofware-Engineering
  - Requirements
Theme: Roles
---


## 📚 Idea/Concept 

Latency is a quality attribute that measures time to first byte, or the time elapsed from the moment a request is sent until the system initiates a response. It is broken down into network latency (data transmission) and processing latency, which includes internal delays such as deserialization, database access, or calls to dependent services. Additionally, client latency can be considered, which encompasses input, rendering, and display (motion-to-photon) times. This attribute is quantified using percentiles such as P90 or P99 and is part of Service Level Agreements (SLAs). Its management requires continuous monitoring, redundancy, and failover mechanisms to mitigate its impact, balancing trade-offs with consistency, throughput, and the economic cost of design decisions.
## 📌 Key points (Optional)
- It measures the time to first byte—the delay from sending a request to the system’s initial response—composed of network, processing, and client latency.
- It is quantified using percentiles (P90, P99) and formalized in Service Level Agreements (SLAs) as a key performance metric.

## 🔗 Connections
- [[Application availability]]
- [[Stakeholders]]

