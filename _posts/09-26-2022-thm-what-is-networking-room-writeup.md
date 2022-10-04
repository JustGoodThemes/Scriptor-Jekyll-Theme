---
title: "THM Room Writeup: What is Networking?"
layout: post
date: 2022-09-25
feature_image: images/desk.jpg
tags: [thm]
---

TryHackMe's bite-sized 'What is Networking?' module is meant to teach the fundamentals of computer
networking. I've taken a couple of intro networking classes already, but I've found THM's format to 
be exremely easy to understand and great for learning/review! 

# What is networking? 
A network is a system of interconnected devices (in the case of the internet. Postal systems 
also count as networks!) Networks can be public or private. 

# What is the internet?
The Internet is a giant network! It's made up of multiple smaller networks that are connected. 
The small networks are private networks while the networks that connect the networks are public networks.

History: The ARPANET project in the 1960s by the U.S. Defence Department was the first network 
documented. Today, we use the World Wide Web - invented by Tim Berners-Lee!

# Identifying Devices on a Network
Devices must be able to be identified on a network in order to communicate. Devices all have an Internet 
Protocol (IP) address and a Media Access Control (MAC) address. IP addresses can identify hosts on a 
network - but it can also change devices. They're made up of four octets (0-255) and follow potocols (
a set of standards). Public addresses are used to identify devices across the Internet while private 
addresses are used to identify devices among other devices. MAC addresses are unique addresses - a 
12-character hexadecimal number that is assigned by the factory the physical network interface (microchip 
board on the motherboard) was built at. The first six characters stand for the company and the last 
six is the unique number. Two devices won't have the same MAC address. The MAC address always stays 
with its device. However, MAC addresses can be "spoofed" or faked, where a networked device can pretend 
to be another one by using that one's MAC address. 

# ICMP Ping
Ping is a fundamental network tool that is versatile. It uses Internet Control Message Protocol (ICMP) 
packets to check the connection between devices - does the connection exist? Is the connection 
reliable? Ping measures the time taken for ICMP packets to travel between devices, done by using 
ICMP echo packet and echo reply. Ping can be used against both devices on a network with IP addresses, 
and on websites with URLs. 
Performing a ping is easy: 
``` 
 ping IPaddress/websiteURL
```
