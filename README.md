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
```
├── setup/                               # pfSense, Wazuh, agents, SQL, AD setup
│   ├── ad-dc.md                         # Active Directory Domain Controller setup
│   ├── pfsense.md                       # pfSense firewall/router configuration
│   ├── sql-server.md                    # SQL Server 2022 install & vulnerable configs
│   ├── wazuh.md                         # Wazuh SIEM / Manager setup
│   └── windows-agents.md                # Windows agents onboarding/config
│
├── topology/                            # diagrams and addressing
│   ├── network-topology.png             # network connectivity diagram
│   └── ip-plan.md                       # IP addressing plan
│
├── Roadmap.md                           # upgrades and future lab plans
├── README.md                            # project overview
└── LICENSE                              # license
```

## Current Status
✅ pfSense is routing the lab network
✅ Internet connectivity works across all VMs
✅ Active Directory DNS is centralized and working (Forward + Reverse lookup)
✅ Static IP assignments are persistent (DHCP static mappings + clean routing)
✅ SQL Server is set up and accessible
✅ WebAppDB and LabDB are created with tables and sample data
✅ Wazuh server is running
✅ Kali (SOC) can connect and generate alerts in Wazuh

## Disclaimer
This lab is for learning offensive and defensive security research in an isolated environment.

> ⚠️ This repo will evolve: more scenarios, detections, and defenses will be added over time.
