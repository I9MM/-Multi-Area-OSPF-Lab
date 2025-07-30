# 🌐 Multi-Area OSPF Lab

As part of my Network Infrastructure training at NTI (Week 3), I designed and implemented a multi-area OSPF topology using Cisco Packet Tracer.

The lab simulates how large organizations manage internal and inter-branch communication using a hierarchical routing structure:

- Area 0 (Backbone) – representing the Headquarters Call Center in Cairo  
- Area 1 – representing the Alexandria Branch  
- Area 2 – representing the Mansoura Branch  

Each area (branch) can handle internal communication independently. However, if Alexandria (Area 1) needs to communicate with Mansoura (Area 2), the traffic must pass through Cairo (Area 0), just like routing calls through a central call center.

## 🔧 In this lab:

- **Router 3** functioned as a Backbone Router (BR) — it operates fully within Area 0 and handles routing between different ABRs.  
- **Router 4** acted as an Area Border Router (ABR) — it connects Area 1 to the backbone and forwards routing information between them.  
- **Router 5** acted as an ABR — connecting Area 2 to Area 0, bridging Mansoura to the core network.  
- **Router 6** functioned as a Backbone Router (BR) — responsible for internal routing inside Area 0.  
- **Router 7** served as an ABR — connected to Area 1 and Area 0, facilitating traffic between another Alexandria subnet and the backbone.  

## 💡 What I learned:

- How to structure and organize large-scale networks using multi-area OSPF to handle complexity and support future growth.  
- The role of ABRs in linking internal areas to the backbone, and BRs in managing inter-area traffic entirely within Area 0.  

This lab helped me understand how real-world enterprise networks are designed to be modular, scalable, and highly reliable — just like a national call center system ensuring smooth communication across all its branches.

---
