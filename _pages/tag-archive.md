---
title: "Posts by Lab Challenges"
permalink: /lab challenges/
layout: lab challenges
author_profile: true
---
# WEEK 1 LAB CHALLENGE
**Problem Statement:** EXAMINE TCP/IP AND OSI MODELS  
**Approach:**  Worked through modules on file system navigation, installing, and using Packet Tracer.
**Tools:** I used Packet Tracer
- a screenshot of the lab challenge
![Screenshot (263)](https://github.com/user-attachments/assets/23cd2dce-7db8-4206-a875-752dd4d199fd)

---
# WEEK 2 LAB CHALLENGE
**Problem Statement:** BUILD A SWITCH AND A ROUTER, INTRODUCTION TO NETWORK TRAFFIC ANALYSIS

**Approach:** To approach this challenge, I first used Cisco Packet Tracer to simulate a basic network setup. I configured a switch and a router, and connected multiple end devices to create a small LAN. I assigned IP addresses, set up routing protocols, and verified connectivity using ICMP (ping).

Once the topology was operational, I initiated traffic between devices and began analyzing it using HTB Academy's traffic capture tools. I inspected packet flows, ARP requests, and ICMP echo replies to understand how devices communicated across the network.

I focused on:

Identifying common protocols (e.g., ICMP, ARP)

Understanding MAC and IP address resolution

Observing how routers forward packets between networks

Capturing and interpreting packet details using simulated packet capture tools

This hands-on setup helped reinforce foundational networking concepts and gave practical exposure to analyzing traffic at different OSI layers.


**Tools:** I used Packet Tracer and HTB Academy
**Key lesson Learnt:** 
Understanding how routers and switches operate at different OSI layers is crucial for effective network design and troubleshooting.

ARP and ICMP are foundational protocols that reveal much about how devices find and communicate with each other.

Network segmentation, even in small topologies, highlights the importance of correct routing and addressing.

Simulated environments like Packet Tracer are excellent for learning without requiring physical hardware.

---
# WEEK 3 LAB CHALLENGE
**Problem Statement:** Explore DNS in Details and HTTP Web Request mechanisms through hands-on labs in TryHackMe and HTB Academy.
**Approach:** I began with **TryHackMe’s "DNS in Detail"** room, where I explored the foundational DNS components, including:
- DNS resolution (recursive vs. iterative queries)
- Record types (A, AAAA, MX, CNAME, TXT)
- Reverse lookups and DNS zone transfers

I performed active enumeration using tools like `dig`, `host`, and `nslookup` and captured real-time DNS traffic with **Wireshark** to visually understand the structure of query/response packets.

In parallel, I completed the **HTB Academy "Web Requests" module**, where I analyzed:
- HTTP request methods: GET, POST, PUT, DELETE
- HTTP status codes and headers
- Cookie behavior and session persistence
- Web forms and how they submit data to the server

I used **Burp Suite** to intercept and modify HTTP requests and performed lab-based exercises to manipulate parameters, observe server behavior, and identify vulnerabilities.

---

### **Tools Used:**
- TryHackMe (DNS in Detail room)  
- HTB Academy (Web Requests module)  
- Wireshark  
- `dig`, `nslookup`, `host` (DNS tools)  
- Burp Suite  
- Browser Developer Tools  

---

### **Key Lessons Learned:**
- **DNS Enumeration** reveals valuable insight into network infrastructure and can be a stepping stone in recon during penetration testing.
- **Zone Transfers** can leak entire DNS zone data if improperly secured.
- **HTTP Methods** behave differently and must be understood for both offensive and defensive purposes—e.g., `POST` may be used to inject payloads.
- **Burp Suite** is a powerful tool for intercepting and analyzing HTTP requests, helping to identify flaws such as insecure form submissions, parameter tampering, and weak session management.
- **Hands-on traffic analysis** using Wireshark and Burp clarified the raw structure of network traffic that tools often abstract away.







