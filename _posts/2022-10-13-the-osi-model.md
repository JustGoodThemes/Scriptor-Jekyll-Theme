---
title: "The OSI Model: Basics"
layout: post
date: 2022-10-13
feature_image: images/open_source.jpg
tags: [osi, networking, basics]
---

The OSI model is a fundamental conceptual/reference model that was created by the International Organization for Standardization to describe network communication. OSI stands for Open Systems Interconnection. The OSI model is a generic, protocol-independent model. There is another model called the TCP/IP model, but that one is for more specific communication issues and is based on specific standard protocols.

<!--more-->

The OSI model consists of 7 layers that each have their own responsibilities. The layers are as follows: 
<br>
7. [Application](#layer-7-application-layer)
6. [Presentation](#layer-6-presentation-layer)
5. Session
4. Transport
3. Network
2. Data Link
1. Physical
<br>
A good mnemonic is <span style = "color:purple;">*All People Seem To Need Data Processing*</span>.
<br>
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
