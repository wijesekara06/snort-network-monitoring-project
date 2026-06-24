# Network Monitoring with Snort

## Project Overview

This project was completed as part of the DG Interns Hub Cybersecurity Internship Program.

The objective was to deploy and configure Snort 3 in a Kali Linux virtual environment, analyze network traffic, create custom intrusion detection rules, and validate alerts using controlled security testing tools.

---

## Project Objectives

* Understand Intrusion Detection Systems (IDS)
* Install and configure Snort 3
* Capture and analyze network traffic using Wireshark
* Develop custom Snort detection rules
* Test rules using Nmap, Ping, and Curl
* Review generated alerts and findings

---

## Tools Used

* Kali Linux
* Snort 3
* Wireshark
* Nmap
* Curl
* VMware Workstation

---

## Lab Environment

| Component       | Details         |
| --------------- | --------------- |
| Host OS         | Windows 11      |
| Guest OS        | Kali Linux      |
| IDS             | Snort 3         |
| Packet Analyzer | Wireshark       |
| Scanner         | Nmap            |
| Network Type    | NAT / Host-Only |

---

## Custom Snort Rules Created

### Port Scan Detection

* SYN Scan Detection
* NULL Scan Detection
* XMAS Scan Detection

### ICMP Detection

* Ping Burst Detection

### HTTP Threat Detection

* SQLMap User-Agent Detection
* SQL Injection Pattern Detection
* Directory Traversal Detection

---

## Testing Performed

### Nmap

* SYN Scan
* NULL Scan
* XMAS Scan

### Ping

* ICMP Ping Burst Testing

### Curl

* SQLMap User-Agent Simulation
* SQL Injection Simulation
* Directory Traversal Simulation

All testing was performed in an isolated lab environment.

---

## Findings

* All custom Snort rules successfully generated alerts during testing.
* Port scanning activity was detected accurately.
* ICMP burst activity triggered alerts.
* HTTP attack patterns were successfully identified.
* Wireshark captures were used to validate Snort detections.

---

## Project Files

* Project Report (PDF)
* Project Presentation (PPT)
* Snort Rules
* Screenshots
* Supporting Documentation

---

## Future Improvements

* Integration with Wazuh
* Integration with ELK Stack
* Centralized Monitoring Dashboard

---

## Author

W.P. Pawani Madushani

DG Interns Hub Internship Project
