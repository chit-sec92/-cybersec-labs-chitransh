# TryHackMe: Intro to LAN 🖧

## 🧠 Summary

This room introduces Local Area Networks (LANs) — how devices connect and communicate within a private network.  
It explains MAC addresses, ARP protocol, switches, hubs, and network segmentation fundamentals.

This is essential foundational knowledge for both attackers (lateral movement, ARP spoofing) and defenders (understanding local traffic and detecting anomalies).

---

## 📌 Tools & Commands Practiced

- `arp -a` – View ARP table
- `ipconfig` / `ifconfig` – Check IP and interface config
- `ping` – ICMP test
- `netdiscover` – ARP-based LAN discovery
- `nmap -sn <subnet>` – Ping sweep of network

---

## 🔍 Concepts Learned

### 🔸 What is a LAN?
- A **Local Area Network** connects devices in a small physical area like a home, office, or lab.
- Each device gets a **private IP address**.

### 🔸 MAC Address
- Media Access Control (MAC) address is unique to every network device (NIC).
- Format: `00:1A:2B:3C:4D:5E`

### 🔸 Switch vs Hub
- **Hub:** Broadcasts packets to all devices.
- **Switch:** Sends packets only to destination device using MAC address.

### 🔸 ARP Protocol
- ARP = Address Resolution Protocol
- Resolves IP to MAC address
- Stored in **ARP Table** (`arp -a`)

### 🔸 Devices in a LAN
- Computers, printers, routers, switches — all can exist within a LAN.

---

## 🛠️ Hands-On Practice Done

- Explored local subnet IP range using `netdiscover`
- Viewed active hosts with `nmap -sn`
- Understood how ARP poisoning could be abused by attackers
- Visualized internal traffic flow

---

## 📚 References

- [ARP Explained - GeeksForGeeks](https://www.geeksforgeeks.org/working-of-address-resolution-protocol-arp/)
- [TryHackMe: Intro to LAN Room](https://tryhackme.com/room/introtolan)

---

## 🎯 Learning Outcome

- Gained hands-on understanding of how LANs operate
- Learned how to enumerate local devices using ARP-based tools
- Built foundational networking knowledge for Blue Team & Pentesting use cases

