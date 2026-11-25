# Module 02 – Network Protocols, Ports and Services

## 1. Network Protocols

A network protocol is a set of rules that defines how data is communicated and transmitted between devices over a network.

### Purpose

- Enables communication between devices.
- Defines data formats and transmission rules.
- Helps ensure reliable and secure data transfer.

### 1.1 HTTP – Hypertext Transfer Protocol

HTTP is used to transfer web pages between a browser and a web server.

**Features:**
- It is not secure by default.
- Data is sent without encryption.

**Example:** Opening a website using `http://`.

### 1.2 HTTPS – Hypertext Transfer Protocol Secure

HTTPS is a secure version of HTTP that protects communication using TLS encryption.

**Features:**
- Provides secure communication.
- Encrypts data during transmission.

**Example:** Online banking and secure websites.

### 1.3 FTP – File Transfer Protocol

FTP is used to transfer files between a client and a server.

**Features:**
- Supports file uploads and downloads.
- It is not secure by default.

**Example:** Uploading files to a website server.

### 1.4 DNS – Domain Name System

DNS is used to convert domain names into IP addresses.

**Features:**
- Resolves domain names such as `google.com` into IP addresses.
- Helps devices locate servers.

**Example:** When you enter a website name in your browser, DNS helps find its IP address.

### 1.5 SMTP – Simple Mail Transfer Protocol

SMTP is used for sending emails from one mail server to another.

**Features:**
- Used for sending emails.
- Works with mail servers.

**Example:** Sending an email using Gmail.

### 1.6 DHCP – Dynamic Host Configuration Protocol

DHCP automatically assigns IP addresses to devices connected to a network.

**Features:**
- Automatically assigns IP addresses.
- Provides network settings such as subnet mask and default gateway.

**Example:** When you connect your mobile phone to Wi-Fi, the router automatically assigns an IP address to your phone.

### 1.7 ARP – Address Resolution Protocol

ARP is used to find the MAC address of a device using its IP address within a local IPv4 network.

**Features:**
- Finds a MAC address using an IP address.
- Helps devices communicate within a local network.

**Example:** Your laptop wants to send data to a printer on the same Wi-Fi network. It uses ARP to find the printer's MAC address.

### 1.8 ICMP – Internet Control Message Protocol

ICMP is used to send network error messages and check network connectivity.

**Features:**
- Helps identify network connection problems.
- Used by tools such as `ping` and `traceroute`.

**Example:** When you use the `ping google.com` command, ICMP is used to check whether your computer can communicate with the destination.

---

## 2. Real-Life Network Communication Flow

When you open a website:

1. DNS – Converts the domain name into an IP address.
2. TCP – Establishes a connection.
3. HTTP/HTTPS – Transfers the webpage.

**Conclusion:** Network protocols define how devices communicate over a network, making data exchange structured and organized.

---

## 3. Ports and Services

A port is a logical communication endpoint used by devices to send and receive data over a network.

### Purpose

- Identifies specific services on a device.
- Enables multiple services to run on a single IP address.
- Directs network traffic to the correct application.

### Common Ports

| Port Number | Protocol | Service |
|---|---|---|
| 20 | FTP | File transfer (data) |
| 21 | FTP | File transfer (control) |
| 22 | SSH | Secure remote login |
| 23 | Telnet | Remote login (not secure) |
| 25 | SMTP | Sending emails |
| 53 | DNS | Domain name resolution |
| 67, 68 | DHCP | Automatic IP address assignment |
| 80 | HTTP | Web traffic (not secure) |
| 110 | POP3 | Receiving emails |
| 143 | IMAP | Accessing and managing emails |
| 443 | HTTPS | Secure web traffic |
| 445 | SMB | File and printer sharing |
| 3389 | RDP | Remote Desktop access |

### Explanation of Common Ports

**Port 20 and 21 – FTP**
- Used for file transfer.
- Port 20: Data transfer in traditional active FTP.
- Port 21: Control commands.

**Port 22 – SSH**
- Used for secure remote access.
- Commonly used by system administrators.
- Provides encrypted communication.

**Port 23 – Telnet**
- Used for remote login.
- Communication is not encrypted.
- Less secure than SSH.

**Port 25 – SMTP**
- Used for sending emails between mail servers.

**Port 53 – DNS**
- Used to convert domain names into IP addresses.

**Port 67 and 68 – DHCP**
- Used for automatic IP address assignment.
- Port 67: DHCP server.
- Port 68: DHCP client.

**Port 80 – HTTP**
- Used for normal web browsing.
- Data is not encrypted by HTTP itself.

**Port 110 – POP3**
- Used to receive emails from a mail server.
- Commonly downloads emails to a device.

**Port 143 – IMAP**
- Used to access and manage emails on a mail server.
- Keeps emails synchronized across devices.

**Port 443 – HTTPS**
- Used for secure web browsing.
- Data is encrypted using TLS.

**Port 445 – SMB**
- Used for sharing files and printers over a network.
- Commonly used in Windows networks.

**Port 3389 – RDP**
- Used for remote access to Windows computers.
- Allows users to control another computer remotely.

### Real-Life Example

When you use your laptop:

- Port 53 – Resolves a website's domain name.
- Port 443 – Connects to a secure website.
- Port 22 – Connects to a remote Linux server using SSH.
- Port 3389 – Connects to a Windows computer remotely.

**Conclusion:** Understanding common ports helps SOC analysts identify network traffic, investigate suspicious connections, and recognize services running on systems.

---

## 4. Firewalls – Basic Concept

A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predefined rules.

### Purpose

- Protects systems from unauthorized access.
- Blocks malicious traffic.
- Allows safe and trusted communication.
- Acts as a barrier between internal and external networks.

### How a Firewall Works

A firewall checks information such as:

- Source IP address.
- Destination IP address.
- Port number.
- Protocol.

Based on predefined rules, it allows or blocks network traffic.

### Types of Firewalls

**1. Packet Filtering Firewall**
- Checks packets based on predefined rules.
- Fast but provides basic filtering.

**2. Stateful Firewall**
- Tracks active network connections.
- Makes filtering decisions based on connection state.

**3. Application Firewall**
- Filters traffic at the application level.
- Helps protect applications, including web applications.

### Real-Life Example

When you connect to the internet, a firewall checks:
- Is the connection allowed?
- Is the port permitted?
- Does the traffic match a blocking rule?

If the traffic matches an allowed rule, it is permitted. Otherwise, it may be blocked.

**Conclusion:** A firewall is an important security component that protects systems by controlling network traffic and preventing unauthorized access.

---

## 5. Topics to Complete

The original training plan also includes:

- TCP and UDP
- Client-Server Communication

These topics are listed here for completion in a future update.

---

## Key Takeaways

- Protocols define communication rules between devices.
- DNS resolves domain names into IP addresses.
- DHCP automatically assigns network configuration.
- ARP helps find MAC addresses in local IPv4 networks.
- ICMP helps check connectivity and report network errors.
- Ports identify services running on devices.
- Firewalls control network traffic using security rules.

## Interview Questions

1. What is a network protocol?
2. What is the difference between HTTP and HTTPS?
3. What is the purpose of DNS?
4. What is DHCP?
5. What is ARP?
6. What is ICMP?
7. What is a network port?
8. What is the difference between SSH and Telnet?
9. What is the purpose of port 443?
10. What is a firewall?
11. What is the difference between packet filtering and stateful firewalls?
