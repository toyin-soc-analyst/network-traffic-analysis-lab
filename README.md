# 🔍 Network Traffic Analysis Lab (TryHackMe)

This project demonstrates hands-on experience analyzing network traffic to detect malicious activity, including HTTP-based malware delivery and DNS-based command-and-control (C2) communication.

---

## 🎯 Objectives

- Analyze HTTP traffic to identify malicious downloads
- Detect suspicious DNS activity
- Identify C2 communication using DNS TXT records
- Extract hidden flags from network traffic

---

## 🧪 Scenario 1: Malicious PowerShell Download (HTTP)

A user clicked a phishing link which triggered an HTTP request to download a malicious PowerShell file.

### 🔍 Key Findings:
- Identified HTTP response containing a malicious file
- Detected suspicious content type: `application/octet-stream`
- Extracted embedded flag from HTTP payload

### 📸 Evidence:

![HTTP Analysis](http-malware-detection.png)

---

## 🧪 Scenario 2: DNS Data Exfiltration (C2 Communication)

A compromised system communicated with a Command & Control (C2) server using DNS TXT records.

### 🔍 Key Findings:
- Detected suspicious domain: `c2.tryhackme.thn`
- Identified DNS TXT query and response
- Extracted hidden command from TXT record

### 🚨 Flag Found:

### 📸 Evidence:

![DNS Analysis](dns-analysis.png)

![Flag](dns-flag-found.png)

---

## 🧠 Skills Demonstrated

- Network Traffic Analysis
- HTTP & DNS Protocol Analysis
- Threat Detection & Investigation
- Identifying C2 Communication
- SOC Analyst Level 1 Skills

---

## 🛠 Tools Used

- TryHackMe Lab Environment
- Packet Inspection (Simulated Wireshark-style analysis)

---

## 🚀 Conclusion

This lab demonstrates how attackers can:
- Deliver malware via HTTP
- Use DNS as a covert channel for communication

Understanding these techniques is critical for detecting real-world cyber threats.

---

## 🔗 Author

**Oluwatoyin (Toyin)**
- Cybersecurity Enthusiast | SOC Analyst Trainee  
- GitHub: https://github.com/toyin-soc-analyst
- Added Network Traffic Analysis Lab (HTTP & DNS investigation)
