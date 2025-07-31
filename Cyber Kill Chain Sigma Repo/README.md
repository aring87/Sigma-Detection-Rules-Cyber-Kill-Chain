# Sigma Detection Rules for Microsoft Defender

This repository contains custom Sigma rules used in our detection engineering program. These are mapped to MITRE ATT&CK and Cyber Kill Chain phases.

## 📂 Structure

- `rules/windows/process_creation/` – Sigma rules based on Defender DeviceProcessEvents
- `rules/windows/network_connection/` – Network-related detections
- `rules/windows/logon/` – Authentication-based detections

## 🧪 Usage

These rules are designed for Microsoft Sentinel + Defender. They can be converted using [sigmac](https://github.com/SigmaHQ/sigma) or used in native KQL with Sentinel.
