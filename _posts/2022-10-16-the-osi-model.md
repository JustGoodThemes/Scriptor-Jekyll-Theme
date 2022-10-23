---
title: "The OSI Model: Basics"
layout: post
date: 2022-10-16
feature_image: images/OSI_Model.png
tags: [osi, networking, basics]
---

The OSI model is a fundamental conceptual/reference model that was created by the International Organization for Standardization to describe network communication. OSI stands for Open Systems Interconnection. The OSI model is a generic, protocol-independent model. There is another model called the TCP/IP model, but that one is for more specific communication issues and is based on specific standard protocols.

<!--more-->

The OSI model consists of 7 layers that each have their own responsibilities. The layers are as follows: 
<br>
7. [Application](#layer-7-application-layer)
6. [Presentation](#layer-6-presentation-layer)
5. [Session](#layer-5-session-layer)
4. Transport
3. Network
2. Data Link
1. Physical




A good mnemonic is <span style = "color:purple;">*All People Seem To Need Data Processing*</span>.
Let's take a closer look at each layer.



### Layer 7: Application Layer
Protocols are standardized rules so that computers can easily communicate with each other. They determine how users interact with data. The application layer is an abstract layer that specifies the protocols that will be used by devices and ensure that applications can communicate with other applications on other networks and devices. 
The GUI (Graphical User Interface) is part of the application layer, as is everyday applications such as email clients, browsers, and file server browsing software. 
Some Layer 7 protocols are HTTP (Hyper-Text Transfer Protocol), FTP (File Transfer Protocol), SMTP (Simple Mail Transfer Protocol), and Telnet. 
Layer 7 protocols also include DNS (Domain Name System), which is how website addresses are translated into IP addresses for the computer to understand. 



### Layer 6: Presentation Layer
The presentation layer is responsible for standardization. It translates data to and from layer 7. For example, people use different email clients, such as GMail and Outlook. The email must appear the same no matter the client - that's the job of the presentation layer! 
HTTPS is an application layer protocol that uses SSL (a layer 6 protocol), allowing data encryption as a security feature. 
Layer 6 protocols include XDR (Extended Detection and Response, an approach to threat detection and response), TLS (Transport Layer Security, a cryptographic protocol), SSL (Secure Sockets Layer, for establishing an encrypted link between servers and clients), and MIME (Multipurpose Internet Mail Extension, which allows more data types to be sent over mail). 



### Layer 5: Session Layer
The session layer is responsible for creating a connection to another computer (a session). This synchronizes two computers and allows them to send data as small chunks called packets. This layer establishes, manages, and terminates the connections made between the two devices. 
Common session layer protocols include ADSP (AppleTalk Data Stream Protocol), RTCP (Real-time Transport Control Protocol), and PAP (Password Authentication Protocol).



### Layer 4: Transport Layer
The transport layer transmits data across the network. It takes the data from the Application layer, segments the message, adds the source and destination port numbers into the header, and then sends it to the network layer. (Or, the other way, receives data from the network layer, reassembles the segmented data, and sends it up.)
Common protocols at this layer include TCP and UDP. 
TCP (Transmission Control Protocol) is a complex protocol for connection-oriented transmissions and requires a constant connection. It has error checking and is reliable as it guarantees the accuracy of data. This also means that TCP is slower. It's best used for file sharing, internet browsing, and sending emails. 
UDP (User Datagram Protocol), on the other hand, is for connectionless transmissions and does not have error checking or reliability. It is much faster than TCP but does not care whether the data is received or not. This is best used for streaming. 



### Layer 3: Network Layer
The network layer takes care of routing and re-assembly of data. Routing is where the optimal path for data to travel is calculated, with factors such as number of hops and reliability determining the path. The network layer forwards packets to network routers. 
Common layer 3 protocols include ARP (Address Resolution Protocol), ICMP (Internet Control Message Protocol), and IP (Internet Protocol, v4, v6). 



### Layer 2: Data Link Layer
The data link layer is responsible for physical addressing of transmission. This adds the MAC address of the destination to the packet from the network layer. (The MAC is on the NIC Network Interface Card). It has two sublayers: Logical Link Control (LLC) and Media Access Control (MAC). 
LLC is responsible for protocols, flow-control, and giving error messages. 
MAC is for the actual media control. 
The whole layer itself does many things such as error control, synchronizatoin, addressing, and framing. 
Protocols include Ethernet (used to connect devices in a network, known for high speed, reliability, and security) and PPP (Point-to-Point, a protocol used between two routers to transmit multiprotocol data).



### Layer 1: Physical Layer
The physical layer deals with physical connections, such as through ethernet cables, connectors, NIC (network interface cards), and more. 
