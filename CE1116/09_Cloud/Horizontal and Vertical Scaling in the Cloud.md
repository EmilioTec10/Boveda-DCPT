---
Last modification: 2025-08-08 09:06
tags:
  - Cloud
Tema: Development Process
---


## 📚 Idea/Concept 

Horizontal and vertical scaling are two fundamental strategies used to increase the capacity and performance of cloud-based systems. Vertical scaling (scale-up) consists of increasing the computing resources of a single machine—such as CPU, RAM, or storage—but this approach is inherently limited by physical hardware ceilings and often becomes economically inefficient as resource sizes grow. In contrast, horizontal scaling (scale-out) involves adding multiple instances to distribute the workload across many machines. However, this distribution is not automatic: it requires a Load Balancer, the essential engineering component that routes traffic evenly across instances. Modern cloud architectures commonly pair horizontal scaling with auto-scaling mechanisms, enabling dynamic adjustment of capacity and contributing to high availability and resilience. Together, these strategies shape how cloud systems handle increased demand, optimize performance, and maintain reliability.
## 📌 Key points (Optional)
- Horizontal scaling only functions efficiently when supported by a load balancer that distributes traffic across multiple instances.
- Vertical scaling is constrained by physical hardware limits and rapidly increasing costs, making horizontal scaling the preferred strategy for high availability and elasticity.

## 🔗 Connections
- [[IaaS vs PaaS vs SaaS]]
- [[Virtual Private Cloud (VPC)]]
- [[Public IP Address]]