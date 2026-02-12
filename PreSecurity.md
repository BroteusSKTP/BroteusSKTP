**Note:** Official Badges are hyperlinked to the images on the right side of each module header (where applicable). <br>&nbsp;

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
### ✅ 1. Offensive Security Intro
<details> <summary><b>Click to see summary</b></summary>
<br>   
   
* **Status:** Completed on 29/01/2026.
* **Objective:** Hack my first website (legally in a safe environment) and experience an ethical hacker's job.
* **Laboratory Execution:** <br>&nbsp;
     - Established connectivity between Kali Linux (VMware) and the lab network via OpenVPN.
     - Performed directory enumeration using **DirBuster**. <br>&nbsp;
* **Knowledge Base:** Understanding Offensive Security.
</details>

### ✅ 2. Defensive Security Intro
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 30/01/2026.
* **Objective:** Introducing defensive security, what it involves and looks like within the real-world, as well as the technologies involved.
* **Laboratory Execution:** <br>&nbsp;
     - Investigation of possible enumeration attack and application of security measures: <br>&nbsp;
         - IP Address Blocking (Shunning).
         - Rate Limiting implementation for sensitive Administrator endpoints.
         - SIEM Rule configuration against future enumeration attacks. <br>&nbsp;
* **Knowledge Base:** <br>&nbsp;
     - Introduction to Blue Teaming, **Defensive Security** roles and operations.
     - Operational structure of a **SOC** (Security Operations Center) and the role of **SIEM** technology.
</details>

### ✅ 3. Careers in Cyber
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 30/01/2026.
* **Objective:** Learn about the different careers in cyber security.
* **Laboratory Execution:** N/A.
* **Knowledge Base:** <br>&nbsp;
     - Understanding the responsibilities and skillsets for: <br>&nbsp;
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
* **Knowledge Base:** <br>&nbsp;
   - **Network & Internet:** Core definitions and the hierarchy of the web.
   - **Device Identification:** <br>&nbsp;
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
      - **Network:** <br>&nbsp;
         - Handles routing and IP addressing. This is where OSPF (Open Shortest Path First) and RIP (Routing Information Protocol) operate.
         - Data is fragmented and re-assembled here; the Router is a primary Layer-3 device. <br>&nbsp;
      - **Transport:** <br>&nbsp;
         - Responsible for end-to-end communication.
         - **TCP (Transmission Control Protocol):** Reliable and connection-oriented. Guarantees data accuracy (used in Email, Web browsing).
         - **UDP (User Datagram Protocol):** Connectionless and fast. Prioritizes speed over reliability (used in Streaming, VoIP). <br>&nbsp;
      - **Session:** <br>&nbsp;
         - Establishes, manages, and terminates connections (sessions) between devices.
         - Handles authentication and session timeouts.
         - Provides checkpoints to resume data transfers if a failure occurs. <br>&nbsp;
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

### ✅ 5. Extending Your Network
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 06/02/2026
* **Objective:** Learn about some of the technologies used to extend networks out onto the Internet and the motivations for this.
* **Laboratory Execution:**
* **Knowledge Base:**
   - **Introduction to Port Forwarding:**
     
      - Allows external devices on the Internet to access services (Web servers, SSH, etc.) hosted on a private network.
      - Maps a public IP address and port to a specific internal IP and port on the router.
   - **Introduction to Firewalls:**
      - A security device that monitors and filters incoming/outgoing traffic based on established rules.
      - Operates mainly at Layers 3 & 4.
      - Can come in forms of hardware and software (e.g. Snort).
      - **Two Primary Categories:** <br>&nbsp;
         - **Stateful:** <br>&nbsp;
            - Analyzes the behavior of a device based on the entire connection rather than inspecting individual packets.
            - Consumes more resources than stateless firewalls due to its dynamic nature.
            - If a connection from a host is determined to be bad, the firewall can block the entire device from the network. <br>&nbsp;
         - **Stateless:** Filters packets individually based on static rules (IP, Port). Faster and effective against DDoS, but less secure. <br>&nbsp;
      - **Introduction to VPN (Virtual Private Network):** <br>&nbsp;
         - Creates a secure, encrypted "tunnel" over a public network (Internet) to connect remote devices or entire offices.
         - Grants privacy through encryption, anonymity (hiding public IP), and secure access to corporate resources.
         - **Technologies:** <br>&nbsp;
            - **PPP (Point-to-Point Protocol):** Used for authentication and data framing.
            - **PPTP (Point-to-Point Tunneling Protocol):** An older protocol using PPP to tunnel data. Fast but now considered insecure.
            - **IPSec (Internet Protocol Security):** A robust suite of protocols that authenticates and encrypts every IP packet in a session. <br>&nbsp;
      - **LAN Network Devices:**
         - **Router (Layer 3):**
           
            - Routes packets between different networks.
            - Uses routing tables to determine the best path (based on hops, speed, or reliability).
         - **Switch:**
           - **Layer 2 Switch:** Connects devices within the same network using MAC Addresses to forward frames.
           - **Layer 3 Switch:** Combines switch speed with routing capabilities. It can forward both frames and packets (IP-aware).
         - **VLAN (Virtual Local Area Network):**
            - Virtually splits a single physical switch into multiple isolated networks.
            - Prevents unauthorized communication between departments (e.g., Guest VLAN cannot talk to Management VLAN) and reduces broadcast traffic.
</details>

---
## How the Web Works <a href="https://tryhackme.com/BroteusSK/badges/world-wide-web?utm_campaign=social_share&utm_medium=social&utm_content=badge&utm_source=copy&sharerId=6974c172ca9161618aedacbc"><sup><img src="https://github.com/user-attachments/assets/33616203-6b9a-4d14-bf13-77a507088849" width="42.5" height="50" align="right"></sup></a>

---
### ✅ 1. DNS in Detail
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 07/02/2026
* **Objective:** Learn how DNS works and how it helps access internet services.
* **Laboratory Execution:** Utilized `nslookup` commands to query remote authoritative servers.
* **Knowledge Base:**
   - **What is DNS (Domain Name System):**
     
      - "Translates" domain names into IP Addresses.
   - **Domain Hierarchy:**
      - **TLD (Top Level Domain):** <br>&nbsp;
         - The most right-hand part (e.g., `.com`, `.pt`).
         - **gTLD:** Generic (e.g., `.org`, `.net`).
         - **ccTLD:** Country Code (e.g., `.pt`, `.uk`). <br>&nbsp;
      - **Second Level Domain:** The main domain name before TLD, (max 63 chars).
      - **Subdomain:** Additional levels before the SLD (total domain length max 253 chars).
   - **Record Types:**
      - **A/AAAA:** Maps domain names to IPv4 / IPv6 addresses.
      - **CNAME (Canonical Name):** Maps domain names to others (e.g., `shop.site.com` -> `host.site.com`).
      - **MX (Mail Exchange):** <br>&nbsp;
         - Points to mail servers
         - Uses Priority Flags (lower number = higher priority) for redundancy (in case a top priority server is offline). <br>&nbsp;
      - **TXT:** <br>&nbsp;
         - Stores text-based data.
         - Critical for Email Security and Domain Verification. <br>&nbsp;
   - **DNS Request:**
      - **Local Cache Check:** OS checks local storage.
      - **Recursive DNS:** ISP/Local Resolver checks its own cache.
      - **Root Servers:** Directs the query to the correct TLD server.
      - **TLD Servers:** Directs the query to the Authoritative DNS server.
      - **Authoritative Server:** Provides the final record.
      - **Caching & TTL:** The result is cached by the Recursive DNS and the Client for a duration defined by the TTL (Time To Live) in seconds.
</details>

### ✅ 2. HTTP in Detail [ <img width="42.5" height="50" alt="Badge" src="https://github.com/user-attachments/assets/af2391fb-4f55-4bdf-a45a-f6528e8b2997" align="right" />](https://tryhackme.com/BroteusSK/badges/web-fund?utm_campaign=social_share&utm_medium=social&utm_content=badge&utm_source=copy&sharerId=6974c172ca9161618aedacbc)

<details> <summary><b>Click to see summary</b></summary>
<br>
   
* **Status:** Completed on 08/02/2026
* **Objective:** Learn about how to request content from a web server using the HTTP protocol.
* **Laboratory Execution:** Hands-on with `GET`, `POST`, `PUT`, and `DELETE` requests using a TryHackMe web emulator.
* **Knowledge Base:**
   - **HyperText Transfer Protocol (Secure):**
     
      - Set of rules used to communicate with web servers for the transmitting of website data (E.g. HTML, videos....).
      - In the Secure version, the data is encrypted (`Port 443`).
   - **URL (Uniform Resource Locator):**
      - An instruction on how to access a resource on the internet.
      - `http://user:password@tryhackme.com:80/view-room?id=1#task3` <br>&nbsp;
         - **Scheme/Port:** Protocol (`http`) and entry point (`80`).
         - **User:** User credentials if applicable (`user:password`).
         - **Host/Domain:** Domain name or IP address (`tryhackme.com`).
         - **Path:** File name or location (`view-room`).
         - **Query String:** Parameters sent to the server (`?id=1`).
         - **Fragment:** Internal page reference (`#task3`).
   - **Methods:**
      - **GET:** Retrieve data (visible in URL).
      - **POST:** Submit data (e.g., login forms).
      - **PUT:** Update existing records.
      - **DELETE:** Remove data.
   - **Headers:**
      - **Common Request Headers:**
        
         - **Host:** Targeted domain.
         - **User-Agent:** Client browser/OS info.
         - **Content-Length:** Tells the web server how much data to expect in the web request.
         - **Accept-Encoding:** Compression methods that the browser supports.
         - **Cookie:** Sent to server to maintain session.
      - **Common Response Headers:**
         - **Set-Cookie:** Server's instruction to store a session token.
         - **Cache-Control:** Instruction on how/if to store content locally.
         - **Content-type:** Defines data format (HTML, JSON, Image).
         - **Content-Encoding:** Method used to compress the data.
   - **Status Codes:**
      - **2XX - Success:** Request was successful (E.g., `200 OK`, `201 Created`).
      - **3XX - Redirection:** Redirect to a different webpage or website (E.g., `301 Moved Permanently`, `302 Found`).
      - **4XX - Client Errors:** There was an error with the request (E.g., `400 Bad Request`, `401 Not Authorized`, `403 Forbidden`, `404 Page not Found`, `405 Method not Allowed`).
      - **5XX - Server Errors:** Errors happening on server side (E.g., `500 Internal Service Error`, `503 Service Unavailable`).
   - **Cookies:**
      - HTTP doesn't "remember" you. Cookies act as a "ID Badge" (Token).
      - Server sends `Set-Cookie` -> Browser stores it -> Browser sends `Cookie` back on every future request.
</details>

### ✅ 3. How Websites Work
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 09/02/2026
* **Objective:** Learn how websites are created.
* **Laboratory Execution:** <br>&zwnj;
   - HTML basic coding with hyperlinks on a TryHackMe emulator site.
   - Javascript basic coding with changing elements and adding a button on a TryHackMe emulator site.
   - Inspection of source code for credentials on a TryHackMe emulator site.
   - Basic HTML Injection of a malicious link on a TryHackMe emulator site.
     
<table align="center">
  <tr>
    <td>
      <img width="413" alt="image" src="https://github.com/user-attachments/assets/c5fb40e0-5923-4beb-bc64-92ef0c0b7482">
    </td>
    <td>
      <img width="404" alt="image" src="https://github.com/user-attachments/assets/c408a80f-97c3-4d65-b859-07a30acbda24">
    </td>
  </tr>
</table>      <br>&zwnj;

* **Knowledge Base:**      <br>&zwnj;
   - **Front End:** How a browser renders a website.
   - **Back End:** How a web server processes a request and returns a response.
   - **HTML:** <br>&nbsp;
     - Language to build websites and define their structure.
     - Elements/tags are the building blocks and tells browser how to display content. <br>&nbsp;      
       <img width="325" height="193" alt="image" src="https://github.com/user-attachments/assets/6bac1802-e93a-4ce5-aeec-8c463832af4a" /> <br>&zwnj;
     - **`<!DOCTYPE html>`:** Defines the page as a HTML5 document and helps browsers to interpret the page.
     - **`<html>`:** Root element of HTML page.
     - **`<head>`:** Contains information about the page (e.g., page title).
     - **`<body>`:** Document's body and the only thing displayed in the browser.
     - **`<h1>`:** Defines a large heading.
     - **`<p>`:** Defines a paragraph. <br>&zwnj;
     - **Other common attributes:** <br>&zwnj;
        - **Class Attribute:** Can be used to style an element (e.g., `<p class="bold-text">`).
        - **`src` (Source):** Specifies the path to an image or file (e.g., `<img src="img/cat.jpg">`).
        - **Id Attribute:** Identifies an element (e.g., `<p id="example">`).      <br>&zwnj;
   - **JavaScript:**      <br>&zwnj;
      - Allows webpages to be interactive. Can be added via `<script>` tags or externally using `<script src="..."></script>`.
      - **Key Examples:** <br>&zwnj;
         - Selects an element by its ID and modifies its content:
         ```javascript
         document.getElementById("demo").innerHTML = "example"
         ```
          - This command creates a button that, when clicked, triggers JavaScript to find the element with `id="demo"` and change its text to "Button Clicked":
         ```html
         <button onclick='document.getElementById("demo").innerHTML = "Button Clicked";'>Click Me!</button>
         ```   
   - **Sensitive Data Exposure:**      <br>&zwnj;
      - Occurs when sensitive information is left in plain text in the front-end code (e.g., HTML comments).
      - Attackers can use this to find other ways to get in or use credentials to login.
      - When assessing a web page for security measures, page source code should be checked to see if sensitive data was left on comments, javacript or HTML code. <br>&nbsp;
   - **HTML Injection:** A vulnerability where unfiltered user input is rendered as HTML, allowing an attacker to modify the page's appearance or redirect users via malicious links.
        
</details>

### ✅ 4. Putting it all together
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 10/02/2016
* **Objective:** Learn how all the individual components of the web work together.
* **Laboratory Execution:** Quiz about about order of events on an interaction with a webserver: <br>&zwnj;
   - Request tryhackme.com in your browser.
   - Check local cache for IP Address.
   - Check your recursive DNS Server for Address.
   - Query root server to find authoritative DNS Server.
   - Authoritative DNS server advises the IP address for website.
   - Request passes through a WAF (Web Application Firewall).
   - Request passes through a Load Balancer.
   - Connect to webserver on port 80 or 443.
   - Web server receives the GET request.
   - Web application talks to database.
   - Your browser renders the HTML into a viewable website. <br>&zwnj;
* **Knowledge Base:** <br>&zwnj;
   - **Load Balancers:** <br>&zwnj;
      - Ensures the high traffic websites can handle the load.
      - Failsafe in case a web server is not available.
      - Receives request first and then forwards to one of multiple servers decided by an algorithm like: <br>&zwnj;
         - **Round-Robin:** Sends to each server in turn.
         - **Weighted:** Sends to the least busy server. <br>&zwnj;
      - **Health Check:** Periodic checks with each server to ensure they are running correctly. <br>&zwnj;
   - **CDN (Content Delivery Networks):** <br>&zwnj;
      - Hosts static files like JavaScript, images and videos.
      - Thousand servers all around the world.
      - Redirects the request to the nearest physical located server. <br>&zwnj;
   - **Databases:** <br>&zwnj;
      - It's how websites store information for their users.
      - **Some Examples:** `MySQL`, `MSSQL`, `MongoDB` and `Postgres`. <br>&zwnj;
   - **WAF (Web Application Firewall):** <br>&zwnj;
      - Protects the web server by analysing the web requests for common attack techniques.
      - Uses rate limiting to control excessive amount of web requests from an IP, within a specific period.
      - If request is deemed a possible attack, it will be dropped and never sent to the webserver. <br>&zwnj;
   - **Web Server:** <br>&zwnj;
      - Is a software that listens to incoming connections and delivers web content through HTTP Protocol.
      - **Examples:** `Apache`, `Nginx`, `IIS` and `NodeJS`.
      - Delivers files from their root directory, defined by software settings. <br>&zwnj;
   - **Virtual Hosts:** <br>&zwnj;
      - Text-based configuration files.
      - Used by web servers to host multiple websites from different domains.
      - If matched with a hostname HTTP header's request, the right website is provided. If not, the provided website is the default.
      - Can have different root directory locations on the same web server. <br>&zwnj;
   - **Static vs Dynamic Content:** <br>&zwnj;
      - Static Content never changes (e.g., `pictures`, `javascript` and `CSS`).
      - Dynamic Content changes with different requests (e.g., a blog). <br>&zwnj;
         - Those changes are done behind the scenes (Backend) with the use of programming and scripting languages.
         - **Examples:** `PHP`, `Python`, `Ruby`, `NodeJS` and `Perl`.
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
* **Knowledge Base:** <br>&zwnj;
     - A bit of background on Linux.
     - **Basic Commands:** `cd`, `ls`, `cat`, `pwd`.
     - **Search for Files:** `find`, `grep`.
     - **Shell Operators:** `&`, `&&`, `>`, `>>`.
</details>

### ✅ 2. Linux Fundamentals Part 2
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 10/02/2026
* **Objective:** Learn how to log in to a Linux machine using SSH, how to advance commands, file system interaction.
* **Laboratory Execution:** <br>&zwnj;
   - Login to a TryHackMe machine through kali linux using SSH (`ssh username@IP`).
   - **Flags and Switches:** Application of ls `-a`, `--help` and `man`.
   - **Filesystem Interaction:** Application of `touch`, `cp`, `mv`, `mkdir`, `rm` and `file`.
   - **Permissions:** Application of `ls -lh` and `su -l`.
   - **Common Directories:** Explore `/etc`, `/var`, `/root` and `/tmp`. <br>&zwnj;
* **Knowledge Base:** <br>&zwnj;
   - **SSH (Secure Shell):** <br>&zwnj;
      - Protocol between devices in an encrypted form.
      - Allows connection and interaction with a remote machine. <br>&zwnj;
   - **`ls`:** <br>&zwnj;
      - **`-a`:** Shows hidden files.
      - **`--help`:** Shows list of all possible options and brief description.
      - **`man`:** Shows manual pages of information for both system commands and applications.
      - **`-lh`:** Long list format with human-readable file sizes. <br>&zwnj;
   - **`touch`:** Create file.
   - **`mkdir`:** Create folder.
   - **`cp`:** Copy file or folder.
   - **`mv`:** Move a file or folder.
   - **`rm`:** Remove a file or folder.
   - **`file`:** Determine the type of a file. <br>&zwnj;
   - **Permissions:** <br>&zwnj; <br>&zwnj;
     <img width="402" height="78" alt="image" src="https://github.com/user-attachments/assets/6b586ac1-c431-4222-951b-b4f8009aaba1" /> <br>&zwnj;  
      - **r:** `Read` (Value = 4).
      - **w:** `Write` (Value = 2).
      - **x:** `Execute` (Value = 1). <br>&zwnj;
      - **First 3 Bits:** `Owner` (The user who owns the file).
      - **Next 3 Bits:** `Group` (Users in the file's group).
      - **Last 3 Bits:** `Others` (Everyone else on the system).
      - **Users & Groups:** User can own a file and, if permissions have been set, groups of users can have the same or different set of permissions.  <br>&zwnj;
      - **`su`:** Switches user by inputting the respective password. <br>&zwnj;
         - **`-l`:** Switch that allows to inherit more properties of the new user (e.g., environment variables).  <br>&zwnj;
      - **`chmod`:** Modifies file or directory permissions. <br>&zwnj;
         - We need to calculate the numeric value and add them together for each group. For example:
           ``` bash
           chmod 755 example.txt
           ```
            - Owner - Full Access (4 + 2 + 1).
            - Group - Read + Execute (4 + 1).
            - Others - Read + Execute (4 + 1). <br>&zwnj;
   - **Common Directories:** <br>&zwnj;
      - **`/etc`:** Commonplace location to store system configuration files.
      - **`/var`:** Stores data that is frequently accessed or written by services and applications.
      - **`/root`:** Home for the "root" system user.
      - **`/tmp`:**
         - Stores temporary data that gets cleared out when the system resets.
         - Important for pentesting because any user can write in this folder by default.
</details>

### ✅ 3. Linux Fundamentals Part 3
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 11/02/2026
* **Objective:** Hands-on with some common utilities.
* **Laboratory Execution:** <br>&zwnj;
   - Edited and created files using `nano`
   - Started a web server using `python3 -m http.server` and downloaded files with `wget`.
   - Managed processes using `top`, `ps aux`, and `kill`.
   - Inspected scheduled tasks in `crontab` and analyzed system logs in `/var/log`. <br>&zwnj;
* **Knowledge Base:** <br>&zwnj;
   - **Terminal Text Editors:** <br>&zwnj;
      - **`nano`:** Beginner-friendly editor. Features include text search (`Ctrl+W`), line jumping, and position tracking.
      - **`vim`:** Advanced editor with modal editing, syntax highlighting, and high portability across all Unix systems. <br>&zwnj;
   - **General/Useful Utilities:** <br>&zwnj;
      - **`wget`:** Downloads files via HTTP/HTTPS (e.g., `wget https://assets.tryhackme.com/additional/linux-fundamentals/part3/myfile.txt`).
      - **`scp`:** Securely copies files/directories between hosts using SSH encryption. <br>&zwnj; <br>&zwnj;
        <img width="499" height="47.5" alt="image" src="https://github.com/user-attachments/assets/646c2939-8b30-458a-b354-4f6c2ae16336" /> <br>&zwnj;
      - **`http.server`:** Python module to quickly serve files from the current directory (Note: Does not provide directory indexing by default). <br>&zwnj; <br>&zwnj;
           <img width="505" height="55" alt="image" src="https://github.com/user-attachments/assets/e15f53d8-96c6-4a4a-87ef-4d52431c7647" />
           <br>&zwnj;
           <img width="465" height="27.5" alt="image" src="https://github.com/user-attachments/assets/5aa14964-2e76-41d8-aeac-e7fe625df47f" /> <br>&zwnj;
   - **Processes 101:** <br>&zwnj;
      - **PID:** Unique Process ID assigned in order of startup.
      - **Namespaces:** OS feature used to isolate resources (CPU, RAM, Network) so processes remain sandboxed.
      - **systemd:** The first process (**PID 1**) that starts at boot. It is the "parent" of all system processes.
      - **`ps`:** Provides a list of running processes of the user session. <br>&zwnj;
         - **Additional Information:** <br>&zwnj;
            - Status Code.
            - Session that is running it.
            - Usage time of the CPU.
            - Name of the program or command executed.
            - **`aux`:** Shows processes run by other users and the system. <br>&zwnj; <br>&zwnj;
              <img width="606" height="144" alt="image" src="https://github.com/user-attachments/assets/fc195e76-b58e-4d38-89b1-598594b4a619" /> <br>&zwnj;
      - **`top`:** Shows real time statistics about the processes.
      - **`kill`:** Terminates processes. Flags: `SIGTERM` (clean exit), `SIGKILL` (forced exit), `SIGSTOP` (suspend).
      - **`systemctl`:** Allows to interact with systemd process/daemon. <br>&zwnj; <br>&zwnj;
        <img width="217.5" height="32.5" alt="image" src="https://github.com/user-attachments/assets/1e9bbbb0-d512-404e-8aa5-0f81a14d2f75" /> <br>&zwnj;
         - **Options:** <br>&zwnj;
            - **`Start`** Manually starts service.
            - **`Stop`:** Manually stops service.
            - **`Enable`:** Starts on boot.
            - **`Disable`:** Doesn't start on boot.
            - **`Status`:** Running status. <br>&zwnj;
      - **Background & Foreground:** <br>&zwnj;
         - **`Ctrl + Z`:** Pauses a foreground process and sends it to the background.
         - **`&`:** Run command directly in the background.
         - **`fg`:** Brings a background process back to the foreground. <br>&zwnj;
   - **Automation:** <br>&zwnj;
      - **`crontab -e`:** Edits the schedule file. Format: `MIN HOUR DOM MON DOW CMD`. <br>&zwnj;
         - **Values:** <br>&zwnj;
            - **MIN:** What minutes to execute at.
            - **HOUR:** What hour to execute at.
            - **DOM:** What day of the month to execute at.
            - **MON:** What month of the year to execute at.
            - **DOW:** What day of the week to execute at.
            - **CMD:** Command to be executed.
            <br>
            <img width="410" height="24" alt="image" src="https://github.com/user-attachments/assets/f7bbfb5b-ec33-4995-8e5d-ef805e3f0406" /> <br>&zwnj;
   - **Package Management:** <br>&zwnj;
      - **APT:** Advanced Package Tool. Uses repositories and GPG keys to ensure software integrity and updates.
      - **`add-apt-repository`:** Manages third-party software sources (PPAs).
      - **GPG (Gnu Privacy Guard) Key:** Guarantees the integrity of our downloaded software by matching with system trusted keys and developer's.
      - **Steps:** <br>&zwnj;
         - Download the GPG key and use apt-key to trust it.
           <img width="600" height="22.5" alt="image" src="https://github.com/user-attachments/assets/a4905fe5-fda5-4fa8-a90d-842634f2b758" />
         - Add repository to apt source list.
         - Use `nano` or text editor to add and save repository into the list.
           <img width="540" height="52" alt="image" src="https://github.com/user-attachments/assets/ebd3dfc9-b65b-443b-89c5-1d39b7542713" />
         - Use `apt update`.
         - Use `apt install software`. <br>&zwnj;
      - **Remove:** <br>&zwnj;
         - Delete list/file created and use `apt remove software` command.
         - Or `add-apt-repository --remove ppa:PPA_Name/ppa`. <br>&zwnj;
   - **Logs:** Located in `/var/log`. Crucial for monitoring system health and investigating security incidents (e.g., unauthorized access in `auth.log`).

</details>

---
## Windows Fundamentals
---
### ✅ 1. Windows Fundamentals 1
<details> <summary><b>Click to see summary</b></summary>
<br>  
   
* **Status:** Completed on 12/02/2026
* **Objective:** Learn about the Windows desktop, the NTFS file system, UAC, the Control Panel...
* **Laboratory Execution:** <br>&nbsp;
   - Connected to tryhackme windows machine through RDP `xfreerdp3`.
   - Explored Local User and Management for information and user's permissions.
   - Explored Control Panel, Settings and Task Manager. <br>&nbsp;
* **Knowledge Base:** <br>&nbsp;
   - **Windows Editions:** <br>&nbsp;
      - Dominant operating system for in home use and corporate networks.
      - Current version of the Windows operating system for servers is Windows Server 2025.
      - Each new version of the Windows OS brought improved functionality and security. <br>&nbsp;
   - **GUI (Graphical User Interface):** <br>&nbsp;
      - Composed of `The Desktop`, `Start Menu`, `Search Box (Cortana)`, `Task View`, `Taskbar`, `Toolbars` and `Notification Area`.
      - **The Desktop:** Location where shortcuts are displayed for easy access and customizable (note: remote access has restrictions on display settings).
      - **The Start Menu:** <br>&nbsp;
         - Provides access to all programs/apps, files, utility tools, etc... (Windows button).
         - Divided by three sections: <br>&nbsp;
            - **Left Section:** Shortcuts to actions regarding account/login session, Documents/Pictures and Settings.
            - **Middle Section:** Shows all **Recently Added** on top and all the installed app/programs in alphabetical order below.
            - **Right Section:** Default tiles which are icons of specific programs/apps or utilities. <br>&nbsp;
      - **The Taskbar:** Some components are visible by default and any opened apps/programs, folders, files, etc... are shown here.
      - **The Notification Area:** Tipically located at the bottom right corner, displays time, date, volume, internet among other icons. <br>&nbsp;
   - **The File System:** <br>&nbsp;
      - Modern versions of windows use NTFS (New Technology File System).
      - Before there was FAT16/FAT32 (File Allocation Table) that are still used in USB devices or MicroSD cards and HPFS (High Performance File System). <br>&nbsp;
      - **NTFS:** <br>&nbsp;
         - Journaling file system that can automatically repair files on disk using information stored in logs.
         - Supports files larger than 4GB.
         - Set specific permissions on folders and files. <br>&nbsp;
            - To see those permissions `Right Click the file or folder -> Security Tab -> Permissions for Users list` (Credit: Microsoft). <br>&nbsp; <br>&nbsp;
           <img width="631" height="319" alt="image" src="https://github.com/user-attachments/assets/6876a2a1-6d55-455c-82ee-a4aeef1b61d4" /> <br>&nbsp;
         - Folder and file compression.
         - EFS (Encryption File System).
         - **ADS (Attribute Data Stream):** <br>&nbsp;
            - Allows files to contain more than one stream of data.
            - Need 3rd party executables or PowerShell to see.
            - Malware writers have used ADS to hide data. <br>&nbsp;
   - **System32:** <br>&nbsp;
      - **`C:\Windows`:** Folder that usually contains the Windows operating system but can be in a different drive or folder.
      - **`%windir%`:** System environment variable for the Windows directory.
      - Environment variables store information about the operating system environment such as operating system paths, the number of processors used and location of temporary folder.
      - The system32 folder, that resides in Windows directory, contains important files that are critical for the operating system. <br>&nbsp;
   - **User Accounts and Permissions:** <br>&nbsp;
      - User accounts can be Administrator and Standard User.
      - It determines what actions can perform on the Windows system.
      - When an user account is created, a profile is created after first login and will fall under `C:\Users` folder.
      - Have same folders such as `Desktop`, `Documents`, `Downloads`, `Music` and `Pictures`.
      - To determine which users exist on the system: <br>&nbsp;
         - `Start Menu -> type Other User -> Other Users System Settings`. <br>&nbsp;
            - Add someone else to this PC (Administrator).
            - Change account type and Remove. <br>&nbsp;
         - **Local User and Group Management:** `Right Click Start Menu -> Run -> Type lusrmgr.msc`. <br>&nbsp;
            - We can inspect groups and users details and descriptions under the respective folders.
            - An user added to a group (by an Administrator) inherits the groups access permissions. <br>&nbsp;
   - **UAC (User Account Control):** <br>&nbsp;
      - Protects the local user by limiting system privileges.
      - By default, doesn't apply for Administrator accounts, asking for confirmation when executing high privilege actions. 
      - It reduces the likelihood of Malware compromising. <br>&nbsp;
   - **Settings and Control Panel:** <br>&nbsp;
      - Primary locations to make system changes.
      - To see applications installed in control Panel: `Programs -> Programs and Features`.
      - Both can be accessed from the Start Menu.
      - Control Panel is where more complex settings and actions are made.
      - Can use start menu search bar to locate the desired settings. <br>&nbsp;
   - **Task Manager:** <br>&nbsp;
      - Provides information regarding processes/applications running in the system.
      - Can access by `Right Click Taskbar -> Task Manager` or `Ctrl + Shift + Esc`.
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
