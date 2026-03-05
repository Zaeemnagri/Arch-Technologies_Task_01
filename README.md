# Arch-Technologies_Task_01

## Basic Network Packet Sniffer

A simple network sniffer built in Python that captures and analyzes network packets in real time. This project demonstrates how network traffic can be inspected and how packet structures are organized at different layers of a network.

The sniffer captures packets and displays information such as MAC addresses, IP addresses, TCP ports, flags, and raw data.

The project uses **Scapy**, a powerful Python library for packet manipulation and network analysis.

---

# 🚀 Features

* Capture live network traffic
* Display Ethernet frame details
* Analyze IPv4 packet headers
* Extract TCP segment information
* Show TCP flags
* Display raw packet payload
* Real-time packet monitoring

---

# 🧠 Concepts Covered

This project helps in understanding concepts related to:

* **Computer Networking**
* **Cybersecurity**
* Packet structure
* TCP/IP communication
* Network traffic monitoring

---

# 🛠️ Technologies Used

* Python 3
* **Scapy**

---

# 📦 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/network-sniffer.git
```

### 2️⃣ Navigate to the project directory

```bash
cd network-sniffer
```

### 3️⃣ Install required dependency

```bash
pip install scapy
```

---

# ▶️ Usage

Run the script with administrator/root privileges.

```bash
python sniffer.py
```

The program will start capturing packets and displaying their details in the terminal.

Press **Ctrl + C** to stop the sniffer.

---

# 📊 Example Output

```
Ethernet Frame:
 - Destination: C4:17:FE:FF:6B:05
 - Source: 14:DA:E9:21:FE:EB
 - Protocol: 8

IPv4 Packet:
 - Version: 4
 - Header Length: 20
 - TTL: 64
 - Source: 192.168.0.5
 - Target: 104.16.37.249

TCP Segment:
 - Source Port: 42290
 - Destination Port: 80
 - Sequence: 2273540701
 - Acknowledgment: 964591911

Flags:
 URG: 0 ACK: 1 PSH: 0 RST: 0 SYN: 0 FIN: 0
```

---

# 🔎 Applications

Network sniffers are commonly used for:

* Network monitoring
* Security analysis
* Troubleshooting network issues
* Protocol debugging

Professional tools such as **Wireshark** use similar packet inspection techniques.

---

# ⚠️ Disclaimer

This tool is intended **for educational purposes only**.
Use it only on networks where you have permission to monitor traffic.

---

# 🔮 Future Improvements

* Packet filtering (HTTP, DNS, TCP)
* Save packets to `.pcap` files
* Add graphical interface
* Suspicious traffic detection
* Packet statistics dashboard

---

⭐ If you find this project useful, consider giving the repository a star!
