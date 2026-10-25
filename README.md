# Healthcare ISP Network Design 🏥🌐
**Capstone Project, ECPI University (CYB495)** | Role: Network Architect / Engineer | 4-person team | Oct 2026 – Present

## 📋 Overview
In response to an RFP, our team designed a secure network architecture connecting three healthcare organizations, with planned expansion to three additional cities. The design prioritizes protecting patient data as it moves between sites and across the Internet.

## 🎯 Objectives
- Define current and future network requirements from the RFP
- Securely connect multiple healthcare sites over a WAN
- Protect sensitive patient records through network segmentation
- Build a scalable design that supports future expansion

## 🛠️ Technologies
`WAN` `VLAN` `ACL` `VPN` `Firewalls` `Cisco Packet Tracer`

## 🔐 Security Design Highlights
- **VLAN segmentation:** separates traffic by department and function
- **Firewalls and ACLs:** control traffic between sites and to the Internet
- **Encrypted VPN tunnels:** protect data moving between locations
- **Dedicated security zones:** isolate systems that store patient records

## 👤 My Contributions
- Analyzed the RFP and defined network requirements
- Authored the team's **Network Requirements** report section
- Created the **logical architecture diagram**
- Planned Packet Tracer validation of routing, segmentation, and failover

## 📊 Diagrams
<img width="1686" height="684" alt="image" src="https://github.com/user-attachments/assets/319937cd-eef3-4c4a-b3a7-464d802bccfe" />
### Network Topology (Cisco Packet Tracer)
The topology connects headquarters, Chicago, and Orlando sites to a central data center, with all Internet traffic passing through a Cisco ASA firewall.

- **HQ site:** departmental VLANs (Sales, Marketing, Finance, Operations) with wireless access
- **Chicago branch:** VLANs 10–50 separating workstations, printers, and wireless users
- **Orlando branch:** wired and wireless users plus a network sniffer for traffic monitoring
- **Data center:** spine-leaf switching architecture for redundancy and scalability
- **Perimeter:** Cisco ASA 5506-X firewall between internal sites and the ISP/Internet
## 💡 Skills Demonstrated
Requirements analysis · Network architecture · Secure WAN design · Healthcare data protection · Technical writing · Team collaboration

## 🚧 Status
Topology built in Cisco Packet Tracer. Validation of routing, segmentation, and failover.
