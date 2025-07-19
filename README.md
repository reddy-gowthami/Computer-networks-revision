# 🕸️ Computer Networks Revision Notes

This repository contains a concise and structured summary of key topics in **Computer Networks**, suitable for exam prep, interviews, and quick reference.

---

## 📌 1. Basics of Computer Networks

**Definition**: Interconnection of devices to share data and resources.

### Types of Networks:
- **PAN** – Personal Area Network
- **LAN** – Local Area Network
- **MAN** – Metropolitan Area Network
- **WAN** – Wide Area Network

### Network Topologies:
- Star
- Bus
- Ring
- Mesh
- Hybrid

---

## 📶 2. OSI Model (7 Layers)

| Layer No. | Name               | Data Unit | Functions                                |
|-----------|--------------------|-----------|------------------------------------------|
| 7         | Application         | Data      | End-user services (HTTP, FTP, DNS)       |
| 6         | Presentation        | Data      | Data formatting, encryption/decryption   |
| 5         | Session             | Data      | Manages sessions                         |
| 4         | Transport           | Segment   | TCP (reliable), UDP (unreliable)         |
| 3         | Network             | Packet    | IP addressing, routing                   |
| 2         | Data Link           | Frame     | MAC addressing, error detection (CRC)    |
| 1         | Physical            | Bits      | Transmission media, signal               |

---

## 🌐 3. TCP/IP Model (4 Layers)

- **Application**
- **Transport**
- **Internet**
- **Link (Network Access)**

> 📌 *Note: OSI is theoretical; TCP/IP is practical.*

---

## 🧮 4. IP Addressing

- **IPv4**: 32-bit, e.g., `192.168.1.1`
- **IPv6**: 128-bit, e.g., `2001:0db8:85a3::8a2e:0370:7334`
- **Subnetting**: Divides network into smaller parts
- **CIDR Notation**: e.g., `192.168.0.1/24`

---

## 📍 5. Routing
- **Default Routing**
- **Static Routing**: Manually configured
- **Dynamic Routing Protocols**:
  - Distance Vector: RIP
  - Link State: OSPF
  - Hybrid: EIGRP

> **Routing Table**: Stores best paths.

---

## 🔄 6. Switching Techniques

- **Circuit Switching** – Dedicated path (e.g., Telephone)
- **Packet Switching** – Divides data into packets (e.g., Internet)
- **Message Switching** – Whole message sent and stored (store-and-forward)

---

## 📦 7. Transport Layer Protocols

- **TCP**:
  - Reliable
  - Connection-oriented
  - 3-way handshake
  - Flow & Congestion Control

- **UDP**:
  - Fast
  - Connectionless
  - No delivery guarantee

---

## 🌍 8. Application Layer Protocols

- **HTTP/HTTPS** – Web browsing
- **FTP** – File Transfer
- **SMTP, POP3, IMAP** – Email
- **DNS** – Domain name to IP resolution

---

## ⚠️ 9. Error Detection & Correction

- **Parity Bit**
- **Checksum**
- **CRC (Cyclic Redundancy Check)**
- **Hamming Code**

---

## 🖧 10. Network Devices

| Device   | Function                      |
|----------|-------------------------------|
| Hub      | Broadcasts data to all ports  |
| Switch   | MAC-based data forwarding     |
| Router   | IP-based packet routing       |
| Gateway  | Protocol conversion           |
| Modem    | Modulates/demodulates signals |

---

## 📡 11. MAC Protocols

- **ALOHA** – Pure and Slotted
- **CSMA/CD** – Ethernet (Collision Detection)
- **CSMA/CA** – Wi-Fi (Collision Avoidance)

---

## 🧭 12. DNS & DHCP

- **DNS**: Resolves domain names to IP addresses
- **DHCP**: Dynamically assigns IP addresses to devices

---

## 📉 13. Congestion Control

- **Leaky Bucket**
- **Token Bucket**
- **TCP Congestion Control**:
  - Slow Start
  - Congestion Avoidance
  - Fast Retransmit

---

## 🔐 14. Firewalls & Network Security

- **Firewall**: Filters traffic based on rules
- **Encryption**:
  - Symmetric (e.g., AES)
  - Asymmetric (e.g., RSA)
- **Authentication**:
  - Passwords
  - Digital Signatures

---

## 🧰 15. Network Tools

- **Ping** – Tests connectivity
- **Traceroute** – Traces path to destination
- **Wireshark** – Packet analyzer
- **Netstat** – Shows active connections

---

## 📝 Quick Revision Tips

- Draw and compare OSI vs TCP/IP models.
- Understand data flow from Application → Physical and back.
- Practice subnetting & CIDR calculations.
- Learn basic terminal commands:  
  `ping`, `ipconfig/ifconfig`, `tracert`, `netstat`

---

📘 **For any topic explanation, examples, or diagrams, feel free to contribute or open an issue!**

