# Attacking-and-Detecting-in-homelab
# 🛡️ Phase 2: Attacking & Detection in HomeLab

This project simulates a real-world adversary attacking a vulnerable DMZ web server in a segmented HomeLab environment, with a focus on capturing and detecting data exfiltration events using Splunk SIEM.

---

## 🏗️ Lab Architecture


    [ Attacker ]
    Kali Linux
        |
        v
    [ Firewall ]
    pfSense (IDS/IPS, Routing)
        |
        v
     [ Entry Point / DMZ Server ]
     Metasploitable 2 (No Splunk Agent)
        |
        v
     [ Logging & Detection ]
     Splunk SIEM (Syslog Receiver)

## 🎯 Objectives

- Simulate realistic web server exploitation from external attacker.
- Perform the laternal movement using metasploitable 2. 
- Detect key attacker behaviors through network-based monitoring.
- Emphasize gaps caused by missing endpoint logging agents.

---

## ⚠️ Disclaimer

This repository is intended **solely for educational and demonstrative purposes**.

It showcases my personal skills in cybersecurity, offensive testing, detection engineering, and lab design. The attacks demonstrated here were performed in a **controlled, isolated HomeLab environment** with intentionally vulnerable systems.

> **Do not replicate any of these techniques on systems you do not own or have explicit permission to test.**

I do not take any responsibility for misuse of the material provided in this repository. Always follow ethical hacking practices and abide by local laws and organizational policies.

---
