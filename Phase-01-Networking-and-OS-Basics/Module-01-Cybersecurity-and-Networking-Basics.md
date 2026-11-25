# Module 01 – Cybersecurity and Networking Basics

## 1. Cybersecurity and SOC

### Cybersecurity

Cybersecurity is the practice of protecting systems, networks, and data from unauthorized access, attacks, damage, or theft. It ensures that sensitive information remains secure and systems function safely.

**Example:** Protecting organizational data from cyber threats such as hacking, malware, and data breaches.

### SOC (Security Operations Center)

A Security Operations Center (SOC) is a centralized team responsible for continuously monitoring, detecting, analyzing, and responding to cybersecurity incidents in an organization.

**Example:** If a hacker attempts to attack a company's system, the SOC team monitors the activity, detects the threat, and takes action to prevent or reduce the impact.

---

## 2. OSI Model

The OSI (Open Systems Interconnection) Model is a conceptual framework used to understand how data travels from one device to another over a network by dividing the communication process into seven layers.

### Purpose

- Standardizes network communication.
- Helps in troubleshooting network issues.
- Makes learning networking easier.

### Seven Layers of the OSI Model

| Layer | Name | Function | Example |
|---|---|---|---|
| 7 | Application | User interaction | Browser (Chrome) |
| 6 | Presentation | Data formatting and encryption | SSL/TLS |
| 5 | Session | Maintains connection | Session management |
| 4 | Transport | Data delivery and error control | TCP/UDP |
| 3 | Network | Routing using IP addresses | IP |
| 2 | Data Link | MAC address and framing | Switch |
| 1 | Physical | Data transmission through cables | Ethernet |

### Data Flow

**When sending data:**

Application → Presentation → Session → Transport → Network → Data Link → Physical

**When receiving data:**

Physical → Data Link → Network → Transport → Session → Presentation → Application

### Mnemonic

"All People Seem to Need Data Processing"

- A – Application
- P – Presentation
- S – Session
- T – Transport
- N – Network
- D – Data Link
- P – Physical

### Real-Life Example

When you open a website:

1. Application – You request a webpage.
2. Transport – Data is broken into packets.
3. Network – Data is routed using IP.
4. Data Link – Uses MAC addresses.
5. Physical – Data is transmitted through cables or wireless signals.

The OSI model helps us understand how data travels step by step through different layers.

---

## 3. TCP/IP Model

The TCP/IP (Transmission Control Protocol/Internet Protocol) Model is a networking framework that explains how data is transmitted over a network using communication protocols.

### Purpose

- Enables communication over a network.
- Defines how data is sent and received.
- Provides a standard for network communication.

### Four Layers of the TCP/IP Model

| Layer | Name | Function | Example |
|---|---|---|---|
| 4 | Application | User interaction | HTTP, FTP, DNS |
| 3 | Transport | End-to-end delivery | TCP, UDP |
| 2 | Internet | Routing using IP addresses | IP |
| 1 | Network Access | Physical transmission | Ethernet |

### Data Flow

**Sending:**

Application → Transport → Internet → Network Access

**Receiving:**

Network Access → Internet → Transport → Application

### OSI vs TCP/IP

| OSI Model | TCP/IP Model |
|---|---|
| 7 layers | 4 layers |
| Theoretical reference model | Practical networking model |

### Conclusion

The TCP/IP model is the foundation of internet communication and defines how data travels between devices.

---

## 4. Types of Networks

A network is a group of interconnected devices that communicate and share data with each other.

### Purpose

- Share resources.
- Enable communication.
- Transfer data between devices.

### 4.1 LAN – Local Area Network

A LAN connects devices within a small geographical area, such as a home, office, or college.

**Examples:**
- Home Wi-Fi network.
- College computer lab network.

**Features:**
- High speed.
- Limited geographical coverage.
- Low cost.

### 4.2 WAN – Wide Area Network

A WAN connects devices over large geographical areas, such as countries and continents.

**Examples:**
- Internet.
- Bank networks.

**Features:**
- Large geographical coverage.
- Generally slower than LAN.
- Can use public networks.

### 4.3 MAN – Metropolitan Area Network

A MAN connects networks across a city or metropolitan area.

**Examples:**
- City-wide internet.
- Cable TV network.

**Features:**
- Medium geographical coverage.
- Generally faster than WAN.
- Generally slower than LAN.

### Network Comparison

| Type | Full Form | Coverage | Relative Speed |
|---|---|---|---|
| LAN | Local Area Network | Small area | High |
| WAN | Wide Area Network | Large area | Lower |
| MAN | Metropolitan Area Network | City | Medium |

### Real-Life Example

When you open a website:

- Your device connects through a LAN.
- Your internet provider connects networks across a wider area.
- The website server may be located in another network or region.

### Conclusion

LAN, MAN, and WAN describe networks based on their geographical coverage and scale.

---

## 5. Topics to Complete

The original training plan also includes these topics under this module:

- IP Address
- MAC Address

These topics are listed here for completion in a future update.

---

## Key Takeaways

- Cybersecurity protects systems, networks, and data.
- SOC teams monitor and investigate security incidents.
- The OSI model has seven layers.
- The TCP/IP model has four layers.
- LAN, MAN, and WAN classify networks by geographical coverage.

## Interview Questions

1. What is cybersecurity?
2. What is a Security Operations Center?
3. What is the OSI model?
4. Name the seven layers of the OSI model.
5. What is the purpose of the TCP/IP model?
6. What is the difference between OSI and TCP/IP?
7. What is the difference between LAN, MAN, and WAN?
