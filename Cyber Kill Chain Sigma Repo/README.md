# Sigma Detection Rules for Microsoft Defender

This repository contains custom Sigma rules used in our detection engineering program. These are mapped to MITRE ATT&CK and Cyber Kill Chain phases.

## 📂 Structure

- Reconnaissance
- Weaponization
- Delivery
- Exploitation
- Installation
- C2
- Actions of Objectives
- Data Exfiltration

## 🧪 Usage

These rules are pretty general and needs to be refined and tuned for specific enviroments and are designed for Microsoft Sentinel + Defender. They can be converted using [sigmac](https://github.com/SigmaHQ/sigma) or used in native KQL with Sentinel.
