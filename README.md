# My Homelab FS3C-RootAndBoot 

A personal cybersecurity homelab built for learning **attack, detection, and defense**.

This lab includes:
- Firewall – pfSense
- SIEM – Wazuh
- AD / Domain Controller – Windows Server (DC01)
- Database – SQL Server 2022 (SQL01)
- Endpoints – Windows + Kali

## Goals
- Practice real-world attack techniques in a safe environment
- Monitor events and alerts
- Apply hardening and defense improvements

## Repo Structure
- `topology/` → diagrams and addressing
- `setup/` → pfSense, Wazuh, agents, SQL, AD setup
- `ROADMAP.md` → upgrades and future lab plans

## Current Status
✅ Wazuh server is running  
✅ pfSense is routing the lab network  
✅ SQL Server is set up and accessible
✅ WebAppDB / LabDB created with tables and sample data  
✅ Kali can connect and generate alerts in Wazuh

## Disclaimer
This lab is for learning offensive and defensive security research in an isolated environment.

> ⚠️ This repo will evolve: more scenarios, detections, and defenses will be added over time.