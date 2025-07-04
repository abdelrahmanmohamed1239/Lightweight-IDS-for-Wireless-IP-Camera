# Sec-T

[ Lightweight-IDS-for-Wireless-IP-Camera ]

A Security Lightweight Intrusion Detection System monitors and protects Tapo IP Camera against Network Threads 

______________________________________________________________________________________________________________

## 📌 Overview  
This project addresses critical cybersecurity vulnerabilities in **wireless IP cameras** (e.g., Tapo, Ezviz, Xiaomi) connected to home/office Wi-Fi networks. These devices are often targeted by **botnets, DoS/DDoS attacks, and unauthorized access** due to weak default security.  

The solution implements a **lightweight Intrusion Detection System (IDS)** using **Suricata NIDS** on a Windows GUI environment, optimized for real-time threat detection without compromising device performance.  

---

## 🎯 Key Features  
- **Hybrid Detection:** Combines **signature-based** (Suricata rules) and **anomaly-based** methods to identify attacks like Mirai botnets, brute force, and RTSP exploits.  
- **Resource Efficiency:** Minimal CPU/memory usage, tailored for low-power IoT devices.  
- **Real-Time Alerts:** Instant notifications for suspicious activities (e.g., unauthorized access).  
- **Scalability:** Adaptable to multi-camera setups and other IoT devices.  
- **Open-Source:** Uses Suricata, Wireshark, and Tapo camera APIs.  

---

## 🛠️ Implementation  
### Tools & Technologies  
- **Suricata NIDS:** Core detection engine with custom rules for IoT threats.  
- **Wireshark:** Packet capture and traffic analysis.  
- **Tapo IP Camera (TC70):** Test device in a 2.4GHz Wi-Fi network.  
- **Windows GUI:** User-friendly interface for non-technical users.  

### Workflow  
1. **Data Collection:** Capture network traffic via Wireshark (PCAP files).  
2. **Threat Detection:** Suricata analyzes traffic for malicious patterns.  
3. **Alerting:** Logs and alerts are generated for anomalies (e.g., DoS attempts).  
4. **Visualization:** LogViewPlus and Kibana for monitoring.  

---

## 📊 Results  
- Successfully detected **malware attacks, botnet traffic, and port scanning**.  
- **<Lowest performance impact** on camera streaming quality.  
- **Accurate detection rate** with optimized Suricata rules.  

---

## 📂 Repository Structure  
```
├── /docs/               # Project report (PDF) and diagrams  
├── /configs/            # Suricata configuration files  
├── /rules/              # Custom IDS rules for IoT threats  
├── /used apps/            # Camera streaming apps and visualization app  
└── README.md  
```

---

## 🚀 Future Work  
- Integrate **machine learning** for adaptive anomaly detection.  
- Extend support for **5GHz networks** and industrial IoT devices.  
- Cloud-based **centralized monitoring dashboard**.
- **IoT attack dataset usage**.  

---

## 📜 License  
Open-source under [MIT License](LICENSE).  

---

## 📬 Contact  
**Abdelrahman Mohamed**  
- Email: [engabdelrahmanmohamed119@gmail.com]  
- LinkedIn: [https://www.linkedin.com/in/abdelrahman-mohamed-31618125b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app]  
