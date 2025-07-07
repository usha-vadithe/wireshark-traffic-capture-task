# Task 5: Wireshark Network Traffic Capture – Cyber Security Internship

## 🎯 Objective
Capture live network traffic using Wireshark and analyze at least three different protocols to understand basic packet flow and real-time network activity.

## 🛠 Tools Used
- Wireshark (v4.x)
- Npcap driver (for packet capture)

## 🔍 Steps Followed

1. Launched Wireshark and selected the active Wi-Fi interface.
2. Started live packet capture.
3. Generated network traffic by:
   - Visiting websites (e.g., google.com, example.com)
   - Running `ping google.com` in Command Prompt
4. Stopped capture after approximately 1 minute.
5. Saved the packet capture as `task5-capture.pcapng`.
6. Identified different protocols using Wireshark’s protocol filters.

## 📡 Protocols Identified

- **DNS** – Used to resolve domain names into IP addresses.
- **TCP** – The base protocol for most communications.
- **HTTP** – Identified during unencrypted web browsing.
- **TLS** – Seen when accessing secure (HTTPS) websites.
- **ICMP** – Detected while pinging websites.

## 📁 Files Included

- `task5-capture.pcapng` – Captured traffic file.
- `traffic_report.txt` – Analysis of protocols and summary of capture.

## ✅ Outcome

Gained hands-on experience in capturing and interpreting real-time network traffic. Learned how to apply protocol filters in Wireshark and recognized various communication protocols that operate on the network layer.

