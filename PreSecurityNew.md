>**Note 1:** Official Badges are hyperlinked to the images on the right side of each module header (where applicable).
>
>**Note 2:** This documentation is based on the path, rooms and machines provided by TryHackMe. All rights to the original instructional material and platform assets are reserved to the respective authors.

## Home Lab Setup
<details> <summary><b>Click to see summary</b></summary> <br>
   
* **Tryhackme.com**
* **Vmware Workstation:**
   - Kali Linux (Rolling Release)
</details>

---
---
## Introduction to Cyber Security
---
### ✅ 1. Offensive Security Intro <a name="offensive-intro"></a>
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#offensive-intro) path. 
> Please refer to that section for the full technical summary and lab execution details.

### ✅ 2. Defensive Security Intro <a name="defensive-intro"></a>
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#defensive-intro) path. 
> Please refer to that section for the full technical summary and lab execution details.

### ✅ 3. Careers in Cyber <a name="careers"></a>
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#careers) path. 
> Please refer to that section for the full technical summary and lab execution details.

---
## Network Fundamentals <a href="https://tryhackme.com/p/BroteusSK?tab=badges"><sup><img src="https://github.com/user-attachments/assets/4e7cfea5-d4f5-45bd-b695-77b30bdc8575" width="42.5" height="50" align="right"></sup></a>
---
### ✅ 1. What is Networking?
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#whatisnet) path. 
> Please refer to that section for the full technical summary and lab execution details.

### ✅ 2. Intro to LAN
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#introalan) path. 
> Please refer to that section for the full technical summary and lab execution details.
    
### ✅ 3. OSI Model
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#osimodel) path. 
> Please refer to that section for the full technical summary and lab execution details.

### ✅ 4. Packets & Frames
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#packets&frames) path. 
> Please refer to that section for the full technical summary and lab execution details.

### ✅ 5. Extending Your Network
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#extendingnet) path. 
> Please refer to that section for the full technical summary and lab execution details.

---
## How the Web Works <a href="https://tryhackme.com/p/BroteusSK?tab=badges"><sup><img src="https://github.com/user-attachments/assets/33616203-6b9a-4d14-bf13-77a507088849" width="42.5" height="50" align="right"></sup></a>

---
### ✅ 1. DNS in Detail
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#dnsdetail) path. 
> Please refer to that section for the full technical summary and lab execution details.

### ✅ 2. HTTP in Detail
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#httpdetail) path. 
> Please refer to that section for the full technical summary and lab execution details.

### ✅ 3. How Websites Work
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#howwebwork) path. 
> Please refer to that section for the full technical summary and lab execution details.

### ✅ 4. Putting it all together
> **Note:** This room was previously completed during the [Pre Security](PreSecurity.md#putting) path. 
> Please refer to that section for the full technical summary and lab execution details.

---
## Computer Fundamentals
---
### ✅ 1. Inside a Computer System
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 24/02/2026.
* **Objective:** Learn the basic components of a computer system.
* **Laboratory Execution:** N/A.
* **Knowledge Base:**
  - **Computer System:**
      - **Motherboard:** Connects and holds all different components together.
      - **CPU (Central Processing Unit):** <br>&nbsp;
         - Executes instructions, utilizing multi-core architecture for parallel processing in modern systems.
         - Connects via CPU socket. <br>&nbsp;
      - **RAM (Random Access Memory):** <br>&nbsp;
         - Holds data temporarily so that the CPU can easily and quickly access it.
         - Uses technologies like DDR4/DDR5 for increased speed and performance. <br>&nbsp;
      - **Storage:** Holds long-term saved data. <br>&nbsp;
         - **HDD:** Holds a large amount of storage capacity and at low cost because it is slower than SSD.
         - **SSD:** Uses memory chips instead of moving parts, so it is faster than HDD.
         - Connects via SATA cables or PCI express ports. <br>&nbsp;
      - **Network Adapter:** <br>&nbsp;
         - Lets computers communicate with other systems.
         - Wireless and wired variants.
         - Embedded in the motherboard or in expansion cards.
         - Connects via PCI Express ports. <br>&nbsp;
      - **PSU (Power Supply):** <br>&nbsp;
         - Supplies energy to all system components.
         - Distributes power from an outlet via main motherboard and Molex connectors. <br>&nbsp;
      - **Graphics Card:** <br>&nbsp;
         - Receives information from the operating system and programs, then outputs processed visual data to a monitor.
         - Connect to PCI Express slots on the motherboard. <br>&nbsp;
      - **Input/Output:** <br>&nbsp;
         - Allows communication between a computer system and the external world.
         - Input devices include keyboards, microphones, mice, and scanners.
         - Output devices include monitors, printers and speakers.
         - Common connectors include USB, HDMI, and DisplayPort. <br>&nbsp;
   - **After Start Button:**
     
      <img width="652" height="72" alt="image" src="https://github.com/user-attachments/assets/fb2728b2-056a-4ebc-a8e4-a606320945cc" />
 
      - **Step 1:** After pressing the start button a signal is sent to the PSU to allow power to flow to all components.
      - **Step 2:** UEFI (Unified Extensible Firmware Interface) or BIOS (Basic Input/Output System) initializes and coordinates components.
      - **Step 3:** POST (Power On Self Test) routine is loaded by the UEFI to test if the required components are present, configured correctly and functioning.
      - **Step 4:** UEFI follows a priority list to determine which device to boot - usually SSD or HDD with OS installed.
      - **Step 5:** The bootloader initializes and transfers the Operating System Kernel into the RAM.
</details>

### ✅ 2. Computer Types
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 24/02/2026.
* **Objective:** Explore the different types of computers.
* **Laboratory Execution:** N/A.
* **Knowledge Base:** <br>&nbsp;
   - **Laptop:** <br>&nbsp;
      - Perfect for emails and documents, but slow to execute long tasks.
      - They are built to be portable, and staying cool in a small, battery-powered device is difficult. <br>&nbsp;
   - **Desktop:** Sustained performance at a fixed location.
   - **Workstation:** Precision and reliability for professional tasks.
   - **Servers:** Provide services to many users over a network.
   - **Smartphone:** Pocket-sized computer optimized for battery life and connectivity.
   - **Tablet:** Touch-first computer with larger screen.
   - **IoT device:** Network-connected device with a single purpose.
   - **Embedded Computer:** Computer built into another device. <br>&nbsp;
   - **IoT vs Embedded:** <br>&nbsp;
      - IoT devices are connected to the internet to report data or receive commands.
      - Embedded computers might not connect to anything and perform dedicated tasks inside the machines they are embedded into.
</details>

### ✅ 3. Client-Server Basics
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 25/02/2026.
* **Objective:** Learn the basics of the Client-Server model.
* **Laboratory Execution:**
* **Knowledge Base:** <br>&nbsp;
   - **Service, Client, Server:** <br>&nbsp;
      - **Service:** A program that provides a specific function to other programs or users.
      - **Client:** A program that requests a service from another program (the server).
      - When using a browser to access a website, the browser is the client and the web server hosting the website is the server. <br>&nbsp;
   - **Request and Response:** <br>&nbsp;
      - The client sends a request to the server, and the server processes the request and sends back a response.
      - If the request was not formatted correctly, or the requested resource was not available, the server sends back an error response. <br>&nbsp;
   - **Protocol:** <br>&nbsp;
      - Defines how a client can communicate with a server. <br>&nbsp;
         - Which commands to the client and the server understand (e.g., **`GET`** command).
         - How a request is structured (e.g., first the command then the order).
         - What syntax is used to format the request (e.g., **`GET /index.html HTTP/1.1`**). 
         - What response should be given to which type of request.
         - What response to give to faulty requests (e.g., 404 Not Found). <br>&nbsp;
   - **Port:** <br>&nbsp;
      - Identifies a specific service running on a system.
      - A server can run multiple services, each listening on a different port. <br>&nbsp;
   - **DNS:** <br>&nbsp;
      - Works similarly to a GPS, when a name of a website is entered, DNS resolves it to a server's location (IP address). <br>&nbsp;
   - **Hypertext Transfer Protocol (HTTP):** <br>&nbsp;
      - Stateless protocol used for communication between clients and servers on the World Wide Web.
      - Mechanisms like token or cookie-based authentication are used to introduce statefulness at the application level. 
      - **Core Commands/Methods:** `GET`, `POST`, `PUT`, `DELETE`, `PATCH`, `HEAD`, `OPTIONS`, `CONNECT`, `TRACE`. 
      - **GET:** Retrieves a resource from a web server. <br>&nbsp;
         - When a user enters a URL in the browser, the browser sends a GET request to the web server..
         - When the web server receives the GET request, it processes it and sends back the status code (header) and the requested information (body).
         - **Developer Tools:** <br>&nbsp;
            - In firefox, `F12` or `right-click -> "Inspect"` opens Developer Tools.
            - The "Network" tab (after reloading the page) shows all network requests made by the browser.
            - By clicking on a request we can inspect details such as: <br>&nbsp;
               - **Scheme:** Protocol used for the request (e.g., HTTP, HTTPS).
               - **Host:** The server's domain name or IP address.
               - **Filename:** The specific file or resource being requested (e.g., `/index.html`).
               - **Address:** The IP address of the server handling the request.
               - **Status:** The HTTP status code returned by the server (e.g., 200 OK, 404 Not Found). <br>&nbsp;
            - The response tab shows the response body in HTML format, which is then rendered by the browser to display the webpage. <br>&nbsp;
</details>

### ✅ 4. Virtualization Basics
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 02/03/2026.
* **Objective:** Learn why virtualization powers modern IT, improving efficiency and safely isolating environments.
* **Laboratory Execution:** N/A.
* **Knowledge Base:** <br>&nbsp;
   - **Virtualization:** <br>&nbsp;
      - `"One server = One application"`. <br>&nbsp;
         - **High cost:** Multiple servers, electricity, cooling, maintenance and data center space.
         - **Low utilization:** Servers had 5–20% usage, wasting CPU, memory, and storage resources.
         - **Slow deployment:** Setting up a new server could take days or weeks.
         - **Hard to scale:** If application needed more resources, it required buying and setting up new hardware. <br>&nbsp;
      - It's the process of creating a virtual version of something, such as a server, storage device, network, or even an entire operating system. <br>&nbsp;
      - Virtualization allows multiple virtual machines (VMs) to run on a single physical machine, sharing its resources while remaining isolated from each other. <br>&nbsp;
   - **Hypervisor:** <br>&nbsp;
      - Software that creates and manages virtual machines. <br>&nbsp;
         - Divides a physical computer into multiple virtual ones.
         - Gives each VM its own virtual hardware (CPU, memory, storage, network interfaces).
         - Keeps everything isolated and safe by preventing VMs from interfering with each other or the host system.
         - Manages life cycle of VMs (start, stop, pause, clone, delete). <br>&nbsp;
      - Types of Hypervisors: <br>&nbsp;
         - **Type 1:** Runs directly on the host's physical hardware, making them fast, efficient, and ideal for servers and professional environments (e.g., VMware ESXi, Microsoft Hyper-V).
         - **Type 2:** Runs within an existing operating system, making them easier to install and ideal for learning, testing, or small setups. (e.g., VMware Workstation, Oracle VirtualBox). <br>&nbsp;
            - When testing malicious files, we need to ensure that the host machine does not become infected by the malware being tested in the guest machine. <br>&nbsp;
   - **Virtual Machine (VM):** A software-based emulation of a physical computer that runs an operating system and applications just like a real computer. <br>&nbsp;
   - **Containers:** <br>&nbsp;
      - A lightweight form of virtualization that allows applications to run in isolated environments.
      - Share the host OS kernel while keeping the application and its dependencies isolated from other containers.
      - Must be compatible with the host OS kernel and architecture. <br>&nbsp;
         - **Docker:** A popular containerization platform that simplifies the process of creating, deploying, and managing containers. <br>&nbsp;
</details>

### 🟡 5. Cloud Computing Fundamentals
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn how cloud computing helps businesses move faster, do more, and scale with less effort.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

---
## Operating Systems Basics
---
### 🟡 1. Operating Systems: Introduction
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Explore the basics of operating systems and the core features.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

### 🟡 2. Windows Basics
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn to navigate Windows, manage files, and use essential system tools.
* **Laboratory Execution:** 
* **Knowledge Base:** 
</details>

### 🟡 3. Linux CLI Basics
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn to navigate through the Linux CLI.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

### 🟡 4. Windows CLI Basics
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Explore what Windows CLI is, how to navigate, and interact with the system using Windows CLI.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

### 🟡 5. Operating System Security
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Introduction to operating system security and SSH authentication on Linux.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

---
## Software Basics
---
### 🟡 1. Data Representation
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn about how computers represent numbers and colors.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

### 🟡 2. Data Encoding
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn how computer encodes characters, from ASCII to Unicode's UTF.
* **Laboratory Execution:** 
* **Knowledge Base:** 
</details>

### 🟡 3. Python: Simple Demo
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Explore a basic Python program.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

### 🟡 4. JavaScript: Simple Demo
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Explore a basic JavaScript program.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

### 🟡 5. Database SQL Basics
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn the basics of databases and SQL.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

---
## Attacks and Defenses
---
### 🟡 1. The CIA Triad
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Understand the CIA Triad and how it shapes cyber security mindset.
* **Laboratory Execution:**
* **Knowledge Base:**
</details>

### 🟡 2. Cryptography Concepts
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn about cryptography.
* **Laboratory Execution:** 
* **Knowledge Base:** 
</details>

### 🟡 3. Become a Hacker
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Explore offensive security, the hacker mindset, and a web app.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

### 🟡 4. Become a Defender
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Explore defensive security, cyber infrastructure, and how to protect systems from attacks.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

### 🟡 5. Database SQL Basics
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** In Progress (Learning & Documenting).
* **Objective:** Learn the basics of databases and SQL.
* **Laboratory Execution:**
* **Knowledge Base:** 
</details>

---

[⬅️ **Back to My Learning Journey**](LearningLabs.md)

*Updated by: Tiago Palaio (BroteusSK).
