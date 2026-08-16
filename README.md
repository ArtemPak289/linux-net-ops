# Linux Net Ops

This repository contains the source code, configuration files, and reports for two comprehensive projects focusing on Linux administration and network engineering. These projects were completed as part of an in-depth DevOps/SysAdmin curriculum.

## Projects Overview

### DO1: Linux Administration Basics (`DO1/src`)
This project covers the fundamental aspects of system administration in Linux (Ubuntu Server). 
Key tasks and topics explored:
- **OS Installation & User Management:** Setting up the OS without a GUI, creating users, and configuring `sudo` privileges.
- **Basic Networking:** Configuring static and dynamic IPs using DHCP, setting up DNS, and troubleshooting with `ping`.
- **System Services:** Configuring time synchronization (NTP) and managing the SSHD service (changing ports, analyzing connections with `netstat`).
- **File System & Storage:** Using utilities like `fdisk`, `df`, `du`, and `ncdu` to manage and analyze disk space.
- **Process & Log Management:** Monitoring system resources with `top` and `htop`, and analyzing system logs in `/var/log`.
- **Automation:** Scheduling tasks using `cron`.
- **Text Editors:** Advanced usage of terminal-based editors like `vim` and `nano`.

### DO2: Linux Networks (`DO2/src`)
This project delves into network configuration, routing, and security using virtual machines to simulate a real-world network topology.
Key tasks and topics explored:
- **IP Addressing & Subnetting:** Calculating networks and masks using `ipcalc`.
- **Static Routing:** Configuring network interfaces with `netplan`, and setting up static routes between multiple machines and simulated routers.
- **Network Diagnostics:** Measuring bandwidth with `iperf3`, tracing routes with `traceroute`, and analyzing packets with `tcpdump`.
- **Firewall Configuration:** Implementing security rules and filtering traffic using `iptables`.
- **Dynamic Host Configuration:** Setting up an `isc-dhcp-server` to assign IPs dynamically, including MAC-address binding.
- **NAT (Network Address Translation):** Configuring SNAT and DNAT to route internal traffic to the external network and expose internal services (like an Apache web server).
- **SSH Tunnels:** Setting up local and remote TCP forwarding.

## Repository Structure
- `DO1/src`: Source files, configuration scripts, and reports for the Linux Administration project.
- `DO2/src`: Source files, configuration scripts, and reports for the Linux Networks project.