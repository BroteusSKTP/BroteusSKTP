## Home Lab Setup
<details> <summary><b>Click to see summary</b></summary>
<br>
   
* **Tryhackme.com**
* **Vmware Workstation:**
   - Kali Linux (Rolling Release)
</details>

---
---
## Introduction to Cyber Security
---
### ✅ 1. Offensive Security Intro
<details> <summary><b>Click to see summary</b></summary>
<br>   
   
* **Status:** Completed on 29/01/2026.
* **Objective:** Hack my first website (legally in a safe environment) and experience an ethical hacker's job.
* **Laboratory Execution:**
     - Established connectivity between Kali Linux (VMware) and the lab network via OpenVPN.
     - Performed directory enumeration using **DirBuster**.
* **Knowledge Base:** Understanding Offensive Security.
</details>

### ✅ 2. Defensive Security Intro
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
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
</details>

### ✅ 3. Careers in Cyber
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 30/01/2026.
* **Objective:** Learn about the different careers in cyber security.
* **Laboratory Execution:** N/A.
* **Knowledge Base:**
     - Understanding the responsibilities and skillsets for:
        - **Security Analysis:** Focus on monitoring and incident response (Blue Team).
        - **Security Engineering:** Building and maintaining secure infrastructure.
        - **Penetration Testing:** Proactive vulnerability assessment (Red Team).
</details>

---
## Network Fundamentals <a href="https://tryhackme.com/BroteusSK/badges/network-fundamentals?utm_campaign=social_share&utm_medium=social&utm_content=badge&utm_source=copy&sharerId=6974c172ca9161618aedacbc"><sup><img src="https://github.com/user-attachments/assets/4e7cfea5-d4f5-45bd-b695-77b30bdc8575" width="42.5" height="50" align="right"></sup></a>
---
### ✅ 1. What is Networking?
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 05/02/2026.
* **Objective:** Begin learning the fundamentals of computer networking.
* **Laboratory Execution:** Used the ping command to verify reachability between hosts.
* **Knowledge Base:**
   - **Network & Internet:** Core definitions and the hierarchy of the web.
   - **Device Identification:**
      - **IPv4:** 32-bit addressing (decimal notation).
      - **IPv6:** 128-bit addressing (hexadecimal notation).
      - **MAC Address:** Physical hardware identification.
</details>

### ✅ 2. Intro to LAN
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
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
</details>
    
### ✅ 3. OSI Model
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 05/02/2026.
* **Objective:** Learn about the fundamental networking framework that determines the various stages in which data is handled across a network
* **Laboratory Execution:** N/A.
* **Knowledge Base:**
   - **Open System Interconnection Model:**

      - Critical model that provides a framework which dictates how all networked devices send, receive and interpret data.
      - **Physical:** Handles the physical hardware and electrical signals (e.g., Ethernet cables, pins, voltages).
      - **Data Link:** Focuses on physical addressing (MAC Address) and framing data for transmission.
      - **Network:**
         - Handles routing and IP addressing. This is where OSPF (Open Shortest Path First) and RIP (Routing Information Protocol) operate.
         - Data is fragmented and re-assembled here; the Router is a primary Layer-3 device.
      - **Transport:**
         - Responsible for end-to-end communication.
         - **TCP (Transmission Control Protocol):** Reliable and connection-oriented. Guarantees data accuracy (used in Email, Web browsing).
         - **UDP (User Datagram Protocol):** Connectionless and fast. Prioritizes speed over reliability (used in Streaming, VoIP).
      - **Session:**
         - Establishes, manages, and terminates connections (sessions) between devices.
         - Handles authentication and session timeouts.
         - Provides checkpoints to resume data transfers if a failure occurs.
      - **Presentation:** Acts as a translator. Handles data encryption, compression, and formatting (e.g., SSL/TLS, JPEG, GIF) so the application can understand it.
      - **Application:** The layer where the user interacts with the network. Protocols like HTTP, FTP, and DNS operate here.
</details>

### ✅ 4. Packets & Frames
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 06/02/2026
* **Objective:** Understand how data is divided into smaller pieces and transmitted across a network to another device.
* **Laboratory Execution:** `nc` (Netcat) for testing port connectivity and basic data transfer.
* **Knowledge Base:**
  - **Data Encapsulation & Units:**
    
      - **Frames (Layer 2):** Data encapsulated with MAC Addresses (Source/Destination). Operates within the local network.
      - **Packets (Layer 3):** Data encapsulated with IP Addresses. Essential for routing data between different networks.
   - **The TCP/IP Model:**
      - **Layers:** Network Interface, Internet, Transport, and Application.
   - **TCP Header & Mechanics:**
      - **Ports:**
        
         - **Source Port:** Randomly assigned from 0 to 65535 if not already in use (Note: Ports 0-1024 are well-known/common ports, so ephemeral source ports are typically chosen from 1025 to 65535).
         - **Destination Port:** Well-known ports (e.g., 80 HTTP, 443 HTTPS, 22 SSH).
      - **Sequence & Acknowledgement:**
         - **ISN (Initial Sequence Number):** A random number to start the conversation.
         - **Sequence Number:** Tracks the number of bytes sent (ensures data order).
         - **Acknowledgement Number:** The next byte the receiver expects to get (Current SEQ + Bytes Received + 1 during handshake).
      - **Checksum:** Integrity check. If the local calculation doesn't match the header, the packet is discarded (detected corruption).
      - **Flags (Control Bits):**
         - 1-bit "switches" that define the packet's purpose.
         - **SYN:** Synchronize (Start connection).
         - **ACK:** Acknowledge (Confirm reception).
         - **FIN:** Finish (Graceful shutdown).
         - **RST:** Reset (Abrupt termination).
      - **The 3-Way Handshake (Establishing Trust):**
         - **SYN:** Client sends an "empty" envelope with a random ISN.
         - **SYN/ACK:** Server acknowledges the Client's ISN and sends its own.
         - **ACK:** Client confirms the Server's ISN and is now open for data.
   - **UDP (User Datagram Protocol):**
      - **Headers:** Much lighter than TCP (Source/Dest Ports/Addresses, Length, Checksum).
      - **TTL (Time To Live):** Contains the expiry timer for the packet. (Note: Technically a field in the IP Header to prevent infinite loops).
</details>

### 🟡 5. Extending Your Network
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn about some of the technologies used to extend networks out onto the Internet and the motivations for this.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

---
## How the Web Works
---
### 🟡 1. DNS in Detail
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn how DNS works and how it helps access internet services.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

### 🟡 2. HTTP in Detail
<details> <summary><b>Click to see summary</b></summary>
<br>
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn about how to request content from a web server using the HTTP protocol.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

### 🟡 3. How Websites Work
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn how websites are created.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

### 🟡 4. Putting it all together
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn how all the individual components of the web work together.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

---
## Linux Fundamentals
---
### ✅ 1. Linux Fundamentals Part 1 [ <img width="42.5" height="50" alt="Badge" src="https://github.com/user-attachments/assets/52883a9b-68b8-43f2-9855-0d353dff8a15" align="right" /> ](https://tryhackme.com/BroteusSK/badges/terminaled?utm_campaign=social_share&utm_medium=social&utm_content=badge&utm_source=copy&sharerId=6974c172ca9161618aedacbc)
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 02/02/2026.
* **Objective:** Learn to run some of the first essential linux commands on an interactive terminal.
* **Laboratory Execution:** Practical application in ubuntu terminal.
* **Knowledge Base:**
     - A bit of background on Linux.
     - **Basic Commands:** `cd`, `ls`, `cat`, `pwd`.
     - **Search for Files:** `find`, `grep`.
     - **Shell Operators:** `&`, `&&`, `>`, `>>`.
</details>

### 🟡 2. Linux Fundamentals Part 2
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn how to log in to a Linux machine using SSH, how to advance commands, file system interaction.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

### 🟡 3. Linux Fundamentals Part 3
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Hands-on with some common utilities.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

---
## Windows Fundamentals
---
### 🟡 1. Windows Fundamentals 1
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn about the Windows desktop, the NTFS file system, UAC, the Control Panel...
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

### 🟡 2. Windows Fundamentals 2
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn about System Configuration, UAC Settings, Resource Monitoring, the Windows Registry...
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

### 🟡 3. Windows Fundamentals 3
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn about the built-in Microsoft tools that help keep the device secure, such as Windows Updates, Windows Security, BitLocker...
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

---

[⬅️ **Back to My Learning Journey**](LearningLabs.md)

*Updated by: Tiago Palaio (BroteusSK).
