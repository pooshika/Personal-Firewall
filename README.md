
# 🔥 Personal Firewall using Python (Linux)

## 🛡️ Objective
Create a custom **personal firewall application** using Python that monitors and filters **incoming and outgoing network traffic** based on IP addresses, ports, and protocols.

---

## 🧰 Tools & Technologies Used

- **Python 3**
- **Scapy** – For packet inspection
- **NetfilterQueue** – Bridge between `iptables` and Python
- **iptables** – Linux firewall for redirecting packets
- **Wireshark (optional)** – For analyzing traffic
- Platform: **Linux** (Tested on Ubuntu)

---

## 🚀 Features

- ✅ Block/Allow traffic based on:
  - Source or destination IP addresses
  - TCP/UDP port numbers
  - Protocol type (e.g., UDP)
- ✅ Real-time console logging of decisions
- ✅ Easy to extend and customize rules
- ✅ Clean shutdown and automatic iptables cleanup

---

## 🖥️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusernam
