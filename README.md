# Home SOC Lab Build

## Overview
This project documents the creation of a home Security Operations Center (SOC) lab designed to simulate, monitor, and analyze security events in a controlled environment. The lab provides hands-on experience with virtualization, networking, and security monitoring tools.

## Lab Architecture
- Host Machine: macOS
- Hypervisor: VMware
- Attacker VM: Kali Linux
- Target VM: Windows 11
- Network Type: Host-Only

## Virtual Machine Setup

### Kali Linux VM
- RAM: 4 GB
- CPU: 2 cores
- Network Adapter: Host-Only
- System updated using `sudo apt upgrade -y`

### Windows VM
- RAM: 4 GB
- CPU: 2 cores
- Network Adapter: Host-Only

## Network Configuration
- Verified IP addresses using `ifconfig` and `ipconfig`
- Initial ICMP traffic was blocked by Windows Firewall
- Created a firewall rule to allow ICMP
- Confirmed connectivity using `ping`


## Security Purpose
This lab supports:
- Attack simulations (DoS, brute force)
- Packet analysis
- Log review and incident response practice

## Outcome
A fully functional home SOC lab capable of supporting security testing, monitoring, and analysis activities.

⚠️ All IP addresses have been redacted.  
This lab was conducted in a controlled environment for educational purposes.
