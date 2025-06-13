#  Personal Firewall using Python

##  Overview

This is a lightweight Python-based personal firewall built for Kali Linux. It uses the Scapy library to sniff live network traffic and enforce rules based on IP addresses, ports, protocols, and DNS queries. Designed for learning, testing, and personal protection, the firewall logs all activity and can be optionally extended with system-level `iptables` blocking or a GUI.

---

##  Features

-  Real-time packet sniffing using Scapy
-  Blocks inbound/outbound IPs
-  Filters ports (e.g., Telnet, SMB)
-  Blocks DNS queries to suspicious or training domains
-  Logs all blocked and allowed packets
-  Optional iptables enforcement
-  Compatible with Kali Linux on VirtualBox

---

##  Tools Used

- Python 3
- Scapy
- iptables
- Kali Linux (VirtualBox VM)

