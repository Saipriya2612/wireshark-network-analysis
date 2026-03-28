# wireshark-network-analysis
Network traffic capture and analysis using Wireshark
# 📡 Wireshark Network Traffic Analysis

## 📌 Overview
This project demonstrates how to capture and analyze network traffic using Wireshark. The goal is to understand how data is transmitted over a network and identify key details within HTTP packets.

---

## 🎯 Objective
- Capture live network traffic  
- Filter HTTP packets  
- Analyze packet-level data  
- Understand security risks of unencrypted communication  

---

## 🛠️ Tool Used
- Wireshark

---

## 📡 Steps Performed

### 1. Installation
Wireshark was downloaded and installed from the official website with default settings.

### 2. Capturing Network Traffic
- Selected the active network interface (Wi-Fi)
- Started packet capture
- Generated traffic by browsing websites

### 3. Filtering HTTP Traffic
- Applied the filter: `http`
- Displayed only HTTP packets for analysis

---

## 🔍 Packet Analysis

### Key Observations:
- Identified **Source IP Address** and **Destination IP Address**
- Observed HTTP request methods such as **GET**
- Analyzed requested resources and host details
- Examined headers like **User-Agent**

### Sample Packet Details:
- Protocol: HTTP  
- Method: GET  
- Source: Local system IP  
- Destination: Web server IP  

---

## ⚠️ Security Findings
- HTTP traffic is **not encrypted**
- Sensitive information can be intercepted easily
- Highlights the importance of using **HTTPS** for secure communication

---

## 🛡️ Conclusion
This project provided hands-on experience with Wireshark and demonstrated how network traffic can be captured and analyzed. It also emphasized the need for secure protocols to protect data during transmission.

---

## 📂 Files Included
- `wireshark_capture.pcap` – Captured network traffic file  
- `README.md` – Project documentation  

---

## 🚀 Learning Outcome
- Gained knowledge of packet capturing  
- Understood HTTP communication  
- Learned basic network traffic analysis  
