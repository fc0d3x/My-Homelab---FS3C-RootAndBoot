# IP Plan

## Lab Subnet
- Subnet: `192.168.X.X/24`
- Gateway (pfSense LAN): `192.168.X.X`

## Hosts
- SOC: `192.168.X.X`
- SQL01: `192.168.X.X`
- Client01: `192.168.X.X`
- DC01: `192.168.X.X`
- Kali: `192.168.X.X`

## Notes
- All VMs route through pfSense
- DNS for domain join points to DC01 (`192.168.X.X`)
