---
title: "THM Room Writeup: Networking Basics"
layout: post
date: 2022-09-25
feature_image: images/cloudnetwork.png
tags: [thm]
---

TryHackMe has a couple of networking basics modules that are meant to teach the fundamentals of computer
networking. I've taken a couple of intro networking classes already, but I've found THM's format to 
be exremely easy to understand and great for learning/review! 

<!--more-->

### What is a network, and what is the Internet?
A network is a system of interconnected devices (in the case of the internet. Postal systems 
also count as networks!) Networks can be public or private. 

The Internet is a giant network! It's made up of multiple smaller networks that are connected. 
The small networks are private networks while the networks that connect the networks are public networks.

History: The ARPANET project in the 1960s by the U.S. Defence Department was the first network 
documented. Today, we use the World Wide Web - invented by Tim Berners-Lee!

### Identifying Devices on a Network - IP and MAC addresses
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

### ICMP Ping
Ping is a fundamental network tool that is versatile. It uses Internet Control Message Protocol (ICMP) 
packets to check the connection between devices - does the connection exist? Is the connection 
reliable? Ping measures the time taken for ICMP packets to travel between devices, done by using 
ICMP echo packet and echo reply. Ping can be used against both devices on a network with IP addresses, 
and on websites with URLs. 
Performing a ping is easy: 
``` 
 ping IPaddress/websiteURL
```

### LAN Topology
LAN stands for Local Area Network. Topology is just the design of a network.

##### Star Topology
Devices are all individually connected to a central networking device, such as a switch or router. This 
topology has a high cost but is also highly reliably and has scalability. All devices are connected to the 
central device so if one fails, it doesn't take down the whole network.

##### Bus Topology
A bus topology has a backbone cable that acts as a single connection, where devices will branch off the backbone 
cable like bus seats on either side of the middle row. It can become slow and bottlenecked because data must 
travel along the same cable, and it also can make it difficult to troubleshoot a failing device. It's a 
cheaper option but has little redundancy (reliability) for failures.

##### Ring Topology (Token Topology)
Devices are connected directly in a loop so there is less reliance on cabling and dedicaed hardware such as 
a switch. Data moves across the loop until it reaches its destination, in only one direction. It's easier to 
troubleshoot but not efficient for sending data as data takes more hops across the network. It won't be slow 
and bottlenecked like a bus topology, but one point of failure will bring down the entire network. 


### Switches and Routers
##### Switch
A switch is a dedicated device that connects multiple devices and keeps track of devices and the port they're 
connected to. switches can have reduced network traffic compared to a hub as they know where their intended 
target of a packet is due to their stored cache and can send the packet directly to the destination.

##### Router
Routers are dedicated devices that connect networks so data can travel. Routing is the process of data 
traveling across networks.

Switches and routers can be connected. This increases the redundancy of a network because data 
packets will have more paths they can take if one fails.

### Subnetting
Subnetting is useful for categorizing parts of a network. It splits up the network and the number of hosts 
that fit within (which is then represented by the subnet mask).

##### Network Address
Identifies the start of the network
##### Host Address
The device's IP address
##### Default Gateway
A special address for a device that can send information to another network, such as a router. Usually the 
first or last host address in a network (.1 or .254). 
Consider a coffee shop with their register and free wifi for customers to use. Subnetting allows to keep these 
devices in different 'sections' of the network.
Subnetting is beneficial because it is efficient, gives full control and more security over your network.


### ARP (Address Resolution Protocol)
ARP allows devices to identify themselves on a network by associating their MAC address with an IP address. 
How it works: A device wants to send a packet to a destination device. They will broadcast a message searching 
for the destination device (ARP Request), asking if their MAC address matches the requested IP address. An 
ARP Reply will be returned if the device has it. The first device will store the ARP entry in its cache.

### DHCP (Dynamic Host Configuration Protocol)
DHCP assigns IP addresses to devices. If a device is not manually assigned one, it can send a DHCP Discover 
request. A DHCP server on the same network can reply with a DHCP Offer, giving the device an IP address it can 
use. The device then must send a DHCP Request reply to confirm taking that IP address, and the DHCP server will 
send a DHCP ACK to acknowledge completion of the transaction.
