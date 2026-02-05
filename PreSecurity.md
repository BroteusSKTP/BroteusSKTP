## Home Lab Setup
* **Tryhackme.com**
* **Vmware Workstation:**
   - Kali Linux (Rolling Release)
---
---
## Introduction to Cyber Security
---
### ✅ 1. Offensive Security Intro
* **Status:** Completed on 29/01/2026.
* **Objective:** Hack your first website (legally in a safe environment) and experience an ethical hacker's job.
* **Laboratory Execution:**
     - Established connectivity between Kali Linux (VMware) and the lab network via OpenVPN.
     - Performed directory enumeration using **DirBuster**.
* **Knowledge Base:** Understanding Offensive Security.

### ✅ 2. Defensive Security Intro
* **Status:** Completed on 30/01/2026.
* **Objective:** Introducing defensive security, what it involves and looks like within the real-world, as well as the technologies involved.
* **Laboratory Execution:**
     - Investigation of possible enumeration attack and application of security measures:
         - IP Address Blocking (Shunning).
         - Rate Limiting implementation for sensitive Administrator endpoints.
         - SIEM Rule configuration against future enumeration attacks.
* **Knowledge Base:**
     - Introduction to Blue Teaming, **Defensive Security** roles and operations.
     - Operational structure of a **SOC** (Security Operations Center) and the role of **SIEM** technology.

### ✅ 3. Careers in Cyber
* **Status:** Completed on 30/01/2026.
* **Objective:** Learn about the different careers in cyber security.
* **Laboratory Execution:** N/A.
* **Knowledge Base:**
     - Understanding the responsibilities and skillsets for:
        - **Security Analysis:** Focus on monitoring and incident response (Blue Team).
        - **Security Engineering:** Building and maintaining secure infrastructure.
        - **Penetration Testing:** Proactive vulnerability assessment (Red Team).
---
## Network Fundamentals
---
### ✅ 1. What is Networking?
* **Status:** Completed on 05/02/2026.
* **Objective:** Begin learning the fundamentals of computer networking.
* **Laboratory Execution:** Used the ping command to verify reachability between hosts.
* **Knowledge Base:**
   - **Network & Internet:** Core definitions and the hierarchy of the web.
   - **Device Identification:**
      - **IPv4:** 32-bit addressing (decimal notation).
      - **IPv6:** 128-bit addressing (hexadecimal notation).
      - **MAC Address:** Physical hardware identification.

### ✅ 2. Intro to LAN
* **Status:** Completed on 05/02/2026.
* **Objective:** Learn about some of the technologies and designs that power private networks
* **Laboratory Execution:** N\A.
* **Knowledge Base:**
   - **Lan Topologies:**
      - **Star Topology:** Reliable and scalable by using centralized robust hardware (Switch/Hub).
         - Expensive due to the high volume of cabling and specialized equipment required.
      - **Bus Topology:** Cost-efficient and simple, using a single backbone cable.
         - Prone to bottlenecks and difficult to troubleshoot if the main cable fails or many devices send data simultaneously.
      - **Ring (Token) Topology:** Devices are connected in a loop and data passes through each device.
         - Uses a "token" system to prevent collisions, making it less prone to bottlenecks, but a single device failure can break the network.
   - **Networking Hardware:**
      - **Switch:** Connects multiple devices within the same network. It uses MAC addresses to track device ports, reducing unnecessary traffic.
      - **Router:** Connects different networks via Routing — the process of directing data packets between distinct networks.
   - **Subnetting:**
      - Using Subnet Masks to split networks into smaller, manageable segments.
         - **Network Address:** Identifies the start and existence of the network.
         - **Host Address:** The specific IP assigned to a device.
         - **Default Gateway:** The entry/exit point for traffic leaving the local network (usually .1 or .254).
   - **Address Resolution Protocol (ARP):**
      - Responsible for mapping IP addresses to MAC addresses.
      - **ARP Cache:** A local table that stores IP-to-MAC mappings.
      - **ARP Request:** A broadcast message asking "Who has this IP?".
      - **ARP Reply:** The response containing the requested MAC address.
   - **Dynamic Host Configuration Protocol (DHCP):**
      - Automatically assigns IP addresses to new devices.
      - **DHCP Discover:** Client broadcasts to find a server.
      - **DHCP Offer:** Server offers an available IP.
      - **DHCP Request:** Client asks to lease that specific IP.
      - **DHCP ACK:** Server confirms and completes the process.
---
## Linux Fundamentals
---
### ✅ 1. Linux Fundamentals Part 1 [ <img width="95" height="100" alt="Badge" src="https://github.com/user-attachments/assets/52883a9b-68b8-43f2-9855-0d353dff8a15" align="right" /> ](https://tryhackme.com/BroteusSK/badges/terminaled?utm_campaign=social_share&utm_medium=social&utm_content=badge&utm_source=copy&sharerId=6974c172ca9161618aedacbc)
* **Status:** Completed on 02/02/2026.
* **Objective:** Learn to run some of the first essential linux commands on an interactive terminal.
* **Laboratory Execution:** Practical application in ubuntu terminal.
* **Knowledge Base:**
     - A bit of background on Linux.
     - **Basic Commands:** `cd`, `ls`, `cat`, `pwd`.
     - **Search for Files:** `find`, `grep`.
     - **Shell Operators:** `&`, `&&`, `>`, `>>`.
---
*Updated by: Tiago Palaio (BroteusSK).
