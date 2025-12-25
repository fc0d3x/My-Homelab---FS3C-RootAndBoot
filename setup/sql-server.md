# SQL Server Setup

## SQL01
- SQL Server 2022 installed on Windows 11 Pro
- TCP/IP enabled
- Port 1433 configured + allowed in firewall
- Mixed Mode Authentication enabled
- Login auditing enabled (success + failure)

## Databases
- WebAppDB
- LabDB

## Verified
- Kali connects remotely using `impacket-mssqlclient`
- Wazuh detects SQL logon failures
