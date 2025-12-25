# pfSense Setup

## What it does
- Routes all lab VMs
- Provides DHCP for the internal subnet
- Forwards logs to Wazuh

## Key points
- LAN gateway: `192.168.X.X`
- DHCP enabled for `192.168.X.X/24`
- Syslog forwarded to SOC (`192.168.X.X`) on UDP 514
