# Malicious npm Package (Supply Chain Attack)

## Description

Attackers compromise or publish malicious npm packages. When a developer installs the package, hidden scripts execute automatically and can steal credentials or exfiltrate data.

---

##  Attack Flow

1. Developer installs npm package
2. Malicious script runs (preinstall/postinstall)
3. Credentials (tokens/API keys) are collected
4. Data is sent to attacker-controlled domain

---

##  Impact

- Theft of GitHub tokens  
- Cloud credential exposure  
- Compromise of CI/CD pipelines  

---

##  MITRE ATT&CK Mapping

- T1195 – Supply Chain Compromise  
- T1059 – Command Execution  
- T1041 – Exfiltration Over C2  

---

##  Real-World Reference

Example: Mini Shai-Hulud supply chain attack (May 2026)
