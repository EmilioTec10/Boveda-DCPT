---
Last modification: 2025-08-08 09:06
tags:
  - Cloud
Tema: Development Process
---


## 📚 Idea/Concept 

A Public IP address is a globally unique network identifier assigned to cloud resources that must be reachable from the internet, such as virtual machines, load balancers, or public-facing APIs. Its primary function is to enable inbound and outbound connectivity over the public internet. However, global accessibility does not imply unrestricted exposure; in production environments, public IPs must be tightly controlled and protected. Public IPs can be either dynamic, changing when resources are restarted or reallocated, or static, remaining fixed and reserved for long-term accessibility—an essential requirement for stable endpoints. Securing a public IP involves restricting incoming traffic to only the necessary ports and protocols, typically enforced through traffic filtering mechanisms such as Network Security Groups (NSGs) or firewall rules, ensuring controlled, least-privilege communication with the resource.
## 📌 Key points (Optional)
- Public IPs may change (dynamic) or remain permanently reserved (static), with static IPs required for stable, long-lived internet-facing services.
- Because public IPs expose resources to the internet, they must be protected using firewalls, Network Security Groups, and strict port filtering to ensure minimal attack surface.

## 🔗 Connections
- [[Hybrid Cloud]]
- [[IaaS vs PaaS vs SaaS]]
