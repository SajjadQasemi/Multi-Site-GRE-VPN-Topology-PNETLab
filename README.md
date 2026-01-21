# Multi-Site-GRE-VPN-Topology-PNETLab
This project demonstrates a multi-site enterprise network using GRE tunnels implemented in PNETLab. Multiple geographic locations are interconnected through GRE tunnels over an ISP core, enabling secure and logical communication between remote branches. The design highlights tunneling concepts, scalable routing, and real-world WAN connectivity.

GRE Tunnel-Based Enterprise Network – PNETLab
📌 Project Overview

This project presents a multi-site enterprise network design based on GRE (Generic Routing Encapsulation) tunnels, implemented and simulated in PNETLab. The topology connects multiple geographically distributed branch offices through an ISP core, enabling logical point-to-point communication over a shared infrastructure.

The main goal of this lab is to demonstrate GRE tunneling concepts, inter-site connectivity, and scalable WAN design used in real-world enterprise networks.

🧠 Network Design Concept

Central ISP Core acting as a service provider

Multiple branch locations connected via GRE tunnels

Logical overlay network built on top of physical IP links

Loopback interfaces used for tunnel sourcing and identification

Each site communicates securely and transparently with other branches through GRE tunnels, regardless of underlying physical paths.

🌍 Sites Included

Kabul

Kandahar

Herat

Mazar

Wardak

Helmand

Each site represents a remote branch with local LAN segments and end devices.

🔐 GRE Tunneling Details

GRE tunnels are established between branch routers and the ISP core

Each tunnel uses a /30 subnet for point-to-point connectivity

Tunnel interfaces encapsulate original IP packets inside new IP headers

Enables routing protocols and private addressing across the WAN

🧪 Verification & Testing

Connectivity and tunnel operation were verified using:

show interface tunnel

show ip route

ping between branch loopback interfaces

End-to-end PC-to-PC connectivity tests

All tunnels successfully pass traffic between sites.

🎯 Learning Objectives

Understand GRE tunnel configuration and operation

Design enterprise-style multi-site WAN topologies

Implement overlay networks over an ISP infrastructure

Practice logical network segmentation and routing

Improve troubleshooting and verification skills

🛠 Tools & Technologies

PNETLab

GRE (Generic Routing Encapsulation)

Cisco IOS Routers

IP Addressing & Subnetting

📂 Usage

This repository can be used for:

Academic projects

Networking practice labs

WAN and tunneling demonstrations

Portfolio and scholarship submissions

👤 Author

Sajjad Qasemi
Network & IT Enthusiast
PNETLab Enterprise Networking Labs![GRE](https://github.com/user-attachments/assets/8a8d0aeb-69ba-40dd-aedd-cbda3dcf59ca)
