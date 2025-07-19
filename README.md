# 🕵️‍♂️ Web Honeypot Forensics with Reverse Shell

A Python Flask-based honeypot designed to simulate and analyze reverse shell attacks in a controlled environment for educational and forensic purposes.

---



## 👨‍💻 Authors
- Muhammad Hasnain (2023S-BCYS-018)  

---

## 🎯 Objective

The primary objective of this project is to design and implement a web-based honeypot capable of capturing and analyzing reverse shell attacks. This enables a deeper understanding of how attackers exploit vulnerable web applications and how forensic techniques can detect, trace, and analyze such attacks.

**Goals:**
- Deploy a web honeypot server to attract attackers
- Simulate a reverse shell attack from a second machine
- Analyze and document attack behavior and forensic evidence

---

## 🔧 Project Walkthrough

### Step 1: Honeypot Server Setup
A basic vulnerable web application was developed using the Python Flask framework. This server served as the target for simulated attacks.

### Step 2: Web Page with Logging Feature
A simple upload-enabled web page was added to the honeypot to track:
- IP addresses of visitors
- Uploaded files and metadata
- Access attempts to restricted resources

### Step 3: Simulated Reverse Shell Attack
From a second machine on the same network (both using Kali Linux), a crafted reverse shell script was uploaded through the honeypot interface.

### Step 4: Remote Shell Access Gained
Upon executing the uploaded script, a reverse connection was established:
- Remote shell access was obtained on the honeypot
- Arbitrary commands could be executed remotely
- Simulated a real-world system compromise

### Step 5: Forensic Data Capture
The honeypot successfully logged all attack activity, including:
- Attacker’s IP address
- Filename, upload timestamp, and location of the uploaded script
- Access logs detailing HTTP requests and executed commands

---

## 🔍 Forensic Insights

The logs collected from the honeypot provide:
- Concrete digital evidence of attack methods
- Behavioral analysis of attacker actions
- Resources for legal, academic, or incident response reporting

---

## ✅ Conclusion

This project successfully demonstrates:
- How a web honeypot can be leveraged to study reverse shell exploitation
- The use of logging and analysis for digital forensics
- The importance of controlled environments in understanding cybersecurity threats

The captured data serves as a valuable tool for enhancing security practices, training forensic analysts, and responding to real-world incidents.

---

## 🛠 Technologies Used
- Python (Flask)
- HTML/CSS (for basic interface)
- Kali Linux (for attacker simulation)
- Reverse Shell Scripting
- Log Analysis

---

