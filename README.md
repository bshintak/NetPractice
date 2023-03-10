# NetPractice

[![Intro](https://img.shields.io/badge/Cursus-NetPractice-success?style=for-the-badge&logo=42)](https://github.com/bshintak/NetPractice)
 
 [![Stars](https://img.shields.io/github/stars/bshintak/NetPractice?color=ffff00&label=Stars&logo=Stars&style=?style=flat)](https://github.com/bshintak/NetPractice)
 [![Size](https://img.shields.io/github/repo-size/bshintak/NetPractice?color=blue&label=Size&logo=Size&style=?style=flat)](https://github.com/bshintak/NetPractice)
 [![Lines of code](https://img.shields.io/tokei/lines/github/bshintak/NetPractice?color=blueviolet)](https://github.com/bshintak/NetPractice)
 [![Activity](https://img.shields.io/github/last-commit/bshintak/NetPractice?color=red&label=Last%20Commit&style=flat)](https://github.com/bshintak/NetPractice)
 
<p align="left">
  <img src=https://raw.githubusercontent.com/bshintak/NetPractice/main/A_Network_Of_Networks.png />
</p>

`Host`

Refers to any device or computer that is connected to the network and has an Internet Protocol (IP) address. We can divide hosts into two categories: clients and servers.
- A client is often a desktop or laptop computer, a smartphone, a video game console, or, with the emergence of the Internet of Things, a smart baby monitor, a seismic or animal habitat surveillance system, a smartwatch, etc.
- A server is a much more powerful machine that stores and distributes web pages, streams videos, transfers email, etc.

A host sends data through a network connection, which can be through an Ethernet cable, Wi-Fi connection, or other network technology. The host uses a communication protocol, such as Transmission Control Protocol/Internet Protocol (TCP/IP), to break down the data into packets and send those packets through the network to the correct recipient. In summary, a host sends data by breaking it down into packets and sending them through the network, where they are routed to the correct recipient.

`The Physical Components of the Internet`

- Network Cables: Network cables are used to connect devices to each other and to the internet. The most common types of network cables are Ethernet cables, which use twisted pair wires to transmit data at high speeds.

- Switches: Switches are devices that connect multiple devices to a network and allow them to communicate with each other. They help to direct data packets to the correct destination.

- Routers: Routers are devices that connect multiple networks together, such as a home network to the internet. They help to route data packets between networks and ensure that data is delivered to the correct destination.

- Modems: Modems are devices that connect a home or business network to the internet. They convert digital data from the network into analog signals that can be transmitted over phone or cable lines.

- Servers: Servers are powerful computers that store and process data and provide services to other devices on the network. They can be used for web hosting, email hosting, file hosting, and many other purposes.

- Data Centers: Data centers are large facilities that house many servers and other networking equipment. They are used to store, manage, and process large amounts of data and provide services to businesses and organizations.

- Wireless Access Points: Wireless access points are devices that provide wireless connectivity to devices on a network. They are commonly used in homes, businesses, and public spaces to provide Wi-Fi access.

`The Internet Protocol Suite`

The Internet Protocol Suite, also known as the TCP/IP protocol suite, is a set of networking protocols used for communication between devices on the Internet. It was developed in the 1970s and consists of several protocols.

- The Internet Protocol (IP) is the primary protocol of the Internet Protocol Suite. It provides the foundation for network communication and is responsible for routing data packets across the network. IP ensures that each data packet is delivered to its destination and identifies each device on the network through its IP address.

- The Transmission Control Protocol (TCP) is another important protocol in the Internet Protocol Suite. It is used to ensure reliable delivery of data and to control the flow of data between devices on the network. TCP establishes a communication connection between devices, enabling bidirectional data transmission.

- The User Datagram Protocol (UDP) is another protocol that is part of the Internet Protocol Suite. It is used for the transmission of data that does not require the reliability provided by TCP. UDP is faster and more efficient than TCP but does not guarantee data delivery or flow control.

- Other application-layer protocols, such as the File Transfer Protocol (FTP), Simple Mail Transfer Protocol (SMTP), and Internet Message Access Protocol (IMAP), are also part of the Internet Protocol Suite.

<p align="left">
  <img src=https://raw.githubusercontent.com/bshintak/NetPractice/main/Internet_Protocol_Layers.png />
</p>

`The Layers of the Internet Model`

Internet’s architectural model is organized in a stack of protocols composed of 5 distinct layers: the application layer, the transport layer, the network layer, the link layer, and finally the physical layer.

- Application layer: This layer is responsible for providing network services to end-user applications. Examples of protocols in this layer include HTTP, FTP, SMTP, and DNS.

Application  |  Protocol(s)  |
---|------|
Request and transfer Web pages | HTTP, HTTPS  |
File transfer	 | FTP  |
Email transfer and access	 | SMTP, IMAP  |
Shell remote access with secure connection	 | SSH  |
Instant message transfer	 | IRC, XMPP  |
Clock synchronization to local time	 | NTP  |
Internet domain name translation into IP address	 | DNS  |
Streaming audio/video	 | RMTP, HLS, SRT  |
Peer-to-peer file sharing	 | BitTorrent, eDonkey  |

- Transport layer: This layer is responsible for providing reliable data transfer between applications running on different hosts. The most common transport layer protocols are TCP and UDP.

- Network layer: This layer is responsible for providing routing and addressing functions that enable packets to be routed between hosts on different networks. The Internet Protocol (IP) is the primary protocol used in this layer. IP, the “Internet Protocol” by definition, naturally dominates the protocols in the Internet’s network layer. This protocol is unrivaled and all of the hosts that have a network layer must run it if they wish to be connected to the Internet. IP defines the network-layer datagram and the IP addresses that uniquely identify every connected host. There are two major versions of IP: IPv4 and IPv6. 

IPv4 (Internet Protocol version 4) is the older version of IP and was the first version to be widely adopted on the Internet. IPv4 uses 32-bit addresses, which allows for a total of around 4.3 billion unique IP addresses. However, with the explosive growth of the Internet, the number of available IPv4 addresses quickly ran out.

To overcome this problem, IPv6 (Internet Protocol version 6) was developed. IPv6 uses 128-bit addresses, which allows for almost an unlimited number of unique IP addresses - more than 340 undecillion addresses, to be more precise. Additionally, IPv6 offers other improvements over IPv4, including better security, scalability, and support for new network features.

- Link layer: This layer is responsible for providing a way to transmit data over a physical network. It includes protocols such as Ethernet and Wi-Fi.

- Physical layer: This layer is responsible for the actual transmission of data over the physical medium, such as copper wires, fiber optic cables, or wireless signals.
