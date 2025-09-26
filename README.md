# Tracenox-Deep-Reinforcement-Learning-for-Adaptive-Cybersecurity-Threat-Forecasting

Tracenox is a real-time, AI-powered Intrusion Detection System (IDS) designed for monitoring, analyzing, and defending network traffic. It integrates deep learning and rule-based heuristics (FSM) for hybrid threat detection, offering high accuracy and adaptive response to evolving network attacks.

---

## Features

- **Real-time Intrusion Detection** using a hybrid Deep Learning + FSM model
- **Network Traffic Monitoring** with live analysis of packet flows
- **Attack Classification** covering DDoS, DoS variants, Web attacks, Bot attacks, Infiltration, Port Scans, and more
- **High Accuracy** with deep learning achieving 96%+ detection
- **Configurable Thresholds** for alerts, confidence margins, and automatic threat blocking
- **File Upload & Testing** for CSV, PCAP, and PCAPNG formats (Max 100MB)
- **Visual Dashboards** for system overview, traffic monitoring, attack timelines, and detailed logs

---

## Security Dashboard

Provides a high-level overview of network health and threat landscape.

![Security Dashboard](images/Screenshot%20(605).png)

- **Total Packets:** 268,038 (+12% from last hour)  
- **Attacks Detected:** 20 (5 critical)  
- **Detection Accuracy:** 96.3%  
- **System Status:** Active, all systems operational  
- **Attack Types Distribution:** DDoS, Web Attacks, Bot Attacks, Infiltration, Port Scan  
- **Attack Timeline (24h):** Hourly detection of attacks  

---

## Real-time Traffic Monitoring

Monitor ongoing network traffic, identify suspicious flows, and classify attacks in real-time.

![Real-time Traffic Monitoring](images/Screenshot%20(606).png)

- **Live Network Traffic Table** with:
  - Timestamp
  - Source & Destination IP
  - Protocol
  - Attack Type & Severity
  - Detection Confidence
  - Number of Packets
- Filter traffic by severity: All / Critical  
- Refresh data in real-time for continuous monitoring  

---

## Upload & Test Network Data

Test and analyze custom network data files or manually input flow information.

![Upload & Test](images/Screenshot%20(607).png)

- **File Upload:** CSV, PCAP, PCAPNG (Max 100MB)  
- **Manual Entry:** Enter network flow features like Source IP, Destination IP, Protocol, and Packet Count  
- **Start Analysis:** Run the hybrid DL+FSM detection on uploaded or manually entered data  

---

## System Settings

Configure detection thresholds, FSM parameters, and system preferences.

![Settings](images/Screenshot%20(609).png)

- **Detection Threshold:** Minimum confidence to trigger alerts  
- **Confidence Margin:** FSM state transition confidence threshold  
- **Log Retention:** Days of logs to retain  
- **Max Concurrent Connections:** Limit for live monitoring  
- **Auto-block Threats:** Automatically block detected malicious traffic  
- **Real-time Monitoring:** Enable continuous traffic analysis  
- **Alert Notifications:** Send alerts for critical threats  
- **System Status:** CPU usage, memory, uptime, and version information  

---

## Installation & Usage

1. Clone the repository:
```bash
git clone https://github.com/yourusername/X-Trace-IDS.git
cd X-Trace-IDS
