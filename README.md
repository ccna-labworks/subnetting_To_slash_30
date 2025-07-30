# subnetting_To_slash_30

# 🧠 Subnetting Practice + Realistic LAN Setup

This lab focuses on Class C subnetting and LAN configuration using `/28` subnets to optimize address allocation and network segmentation. The chosen subnet for this lab is `192.168.1.64/28`, with a reserved range previously used for WAN links.

---

## 📍 Overview

We implemented a **Local Area Network** using a refined subnetting strategy, assigning IPs to a router, switch VLAN, and multiple PCs. Basic connectivity testing and switch gateway setup were included to resolve routing issues.

---

## 🧾 Devices Configured

- ✅ **Router 4**: `192.168.1.78/28`  
- ✅ **Switch 3 VLAN 1**: `192.168.1.77/28`  
- ✅ **PCs**:  
  - PC1: `192.168.1.65`, GW: `192.168.1.78`  
  - PC2: `192.168.1.66`, GW: `192.168.1.78`  
  - PC3: `192.168.1.67`, GW: `192.168.1.78`  
- ✅ **Switch Default Gateway**: Set manually to resolve ping issues:
  ```bash
  ip default-gateway 192.168.1.78

🧪 Useful Commands for Verification
bash
Copy
Edit
show ip interface brief  
show run  
show ip route  
show cdp neighbors detail
These helped verify interface status, routes, and neighbor discovery.

💡 Key Takeaways
Understanding how to correctly assign IP ranges, configure switch VLAN interfaces, and troubleshoot connectivity issues builds essential CCNA-level networking skills. These fundamentals are also key in cloud and security environments where networks form the backbone.

📸 Screenshot Highlights 
Router Interface Configuration

Switch VLAN Setup

PC IP Assignments

Ping/Connectivity Tests

CDP Neighbor Discovery

Routing Table Checks

📂 More Labs & Learning
🔗 Additional labs and diagrams available on my Linkedin:
https://www.linkedin.com/posts/activity-7356230714477993984-FyVD?utm_source=share&utm_medium=member_desktop&rcm=ACoAACymwxoByqlhKmdsE21UETiU_1guDiXo3dQ

📌 Tags
#Networking #CCNA #Subnetting #LANSetup #LearningInPublic #TechJourney #NeverStopLearning

yaml
Copy
Edit
