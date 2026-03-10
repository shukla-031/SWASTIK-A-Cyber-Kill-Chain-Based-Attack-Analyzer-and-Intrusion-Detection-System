# Cyber Kill Chain Intrusion Detection System

A real-time Intrusion Detection System (IDS) built with Python that monitors network traffic and detects suspicious activity such as port scans, brute-force attempts, reverse shell connections, and potential data exfiltration.

The system maps detected attacks to the Cyber Kill Chain stages and displays alerts in a graphical dashboard.


## Features

• Real-time packet monitoring using Scapy
• Detection of common attack patterns
• Cyber Kill Chain stage mapping
• Interactive GUI dashboard using Tkinter
• Attack severity classification
• Network interface selection
• Live packet counter and system stats
• Attack distribution visualization with Matplotlib


## Attack Detection

| Attack Type       | Detection Logic              | Kill Chain Stage     |
| ----------------- | ---------------------------- | -------------------- |
| Port Scan         | Multiple SYN packets         | Reconnaissance       |
| Brute Force       | Repeated login port attempts | Exploitation         |
| Reverse Shell     | Suspicious remote ports      | Command & Control    |
| Data Exfiltration | Large outbound packets       | Action on Objectives |


## Technologies Used

* Python
* Scapy
* Tkinter
* Matplotlib
* Psutil

## Future Improvements

• Machine learning based detection
• Packet logging and analysis
• Threat intelligence integration
• Web dashboard version


## Author

Akshaydeep Shukla
Cybersecurity Enthusiast
