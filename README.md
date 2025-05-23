# Active Directory Home Lab

## Overview

This repository contains resources and documentation to create a functional Active Directory (AD) environment with integrated monitoring and security mechanisms. The lab is inspired by [MyDFIR](https://www.youtube.com/watch?v=5OessbOgyEo).

The project incorporates:
- Windows Server 2022 for Active Directory Domain Services.
- Ubuntu server running Splunk for centralized monitoring.
- A Windows 10 client.
- A Kali Linux machine for simulated attack scenarios.

## Logical Diagram
Below is a link to the logical diagram of the project. The diagram illustrates the network topology, Including a router, switch, 3 authorized nodes and 1 unauthorized node.

<img src="./ad_ld.png" alt="Logical Diagram" width="200">

## Features
1. **Active Directory Setup**
   - Domain Controller configuration
   - User and group management
   - Group Policy enforcement

2. **Centralized Monitoring with Splunk**
   - Sysmon configuration for detailed logging
   - Log forwarding using Splunk Universal Forwarders

3. **Simulated Attack Scenario**
   - Security assessment using brute-force attacks

## Directory Structure
- **`Network_Diagrams/`**: Contains visual diagrams for the lab's network architecture.
- **`Configurations/`**: Configuration files and setup guides for AD, Splunk, and Sysmon.
- **`Scripts/`**: Automation scripts for configuring lab components.
- **`Attack_Simulation/`**: Documentation of attack scenarios and their findings.
- **`Reports/`**: Summary reports of the lab's outcomes and insights.

## Requirements
- **Hardware**: Minimum 16 GB RAM, quad-core CPU.
- **Software**:
  - VMware/VirtualBox
  - Windows Server 2022 ISO
  - Ubuntu 22.04 ISO
  - Splunk free edition
  - Kali Linux ISO
  - Windows 10 ISO

## Credits
This project is heavily inspired by MyDFIR's excellent guide on building an Active Directory home lab.  
Check out the original guide here: [Active Directory Home Lab Guide by MyDFIR](https://www.youtube.com/watch?v=5OessbOgyEo).
