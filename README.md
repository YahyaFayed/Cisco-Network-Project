# Secure Multi-Branch Network Project – Final

This repository contains the final Cisco Packet Tracer project designed to meet all requirements for the "Introduction to Networks" course (CE231) at the Arab Academy for Science and Technology. The project connects four company branches (Cairo, Alexandria, Aswan, and Port Said) with a secure and fully functional network.

## Project Overview
The network was designed according to the following specifications:
- **Four branches**:
  - **Alexandria** – IT Department
  - **Cairo** – Finance Department
  - **Aswan** – Marketing Department
  - **Port Said** – Human Resources Department
- **Branch-specific IP addressing** with suitable network class selection:
  - Aswan: Max 20 hosts
  - Cairo: Max 300 hosts
- **Two or more connected devices per branch** with unique IPs.
- **Router + minimum two switches** per branch.
- **Open Wi-Fi access point** in each branch with at least one connected wireless device.
- **DHCP server per branch** for automatic IP distribution.
- **Centralized webserver and DNS server** in Alexandria, accessible by domain name from all branches.
- **Network topology**:
  - Cairo and Port Said directly connected to Alexandria.
  - Aswan connected to Alexandria via Cairo.

## Features Implemented
- **Servers**:
  - DHCP in all branches.
  - Web & DNS in Alexandria.
- **Switching**:
  - Multiple switches per branch for device interconnection.
- **Routing**:
  - Proper routing configuration between branches.
  - Hierarchical topology matching requirements.
- **IP Addressing**:
  - Correct network class selection for host requirements.
  - Segregated IP ranges for each branch.
- **Wi-Fi**:
  - Configured access points and connected devices.

## Requirements
- Cisco Packet Tracer **8.x or newer** to open the `.pkt` file.

## Usage
1. Download the `.pkt` file from this repository.
2. Open it in Cisco Packet Tracer.
3. Explore device configurations for routing, switching, and server setup.
4. Test connectivity and domain name resolution between branches.



