# 🎯 Microsoft Sentinel Analytics Rules

This repository contains a curated collection of custom **Microsoft Sentinel Analytics Rules** designed to enhance threat detection and support a Zero Trust security strategy.

## 🔍 Overview

The rules included in this repository help detect:

- 🔐 Brute-force and credential stuffing attempts  
- 🌍 Impossible travel and location anomalies  
- 🧑‍💻 Privilege escalation or suspicious role assignments  
- 📤 Sensitive data exfiltration via email  
- 🧬 Endpoint threats (e.g., credential dumping)  
- ☁️ Unusual Azure resource modifications  

Each rule is written in **Kusto Query Language (KQL)** and can be directly imported into Microsoft Sentinel.

## 🚀 Getting Started

To deploy these rules:

1. Open **Microsoft Sentinel** in the Azure portal.
2. Navigate to **Analytics > Create > Scheduled query rule**.
3. Copy the KQL query from the desired `.rule` file.
4. Configure your alert logic, thresholds, and actions.
5. Save and activate the rule.

> Each `.rule` file contains metadata, severity level, MITRE mapping, and the detection logic.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request with new rules, improvements, or suggestions.

---

**Stay secure. Stay ahead.**

