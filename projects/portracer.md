layout: project
type: project
image: img/port_tracer/port_tracer.png
title: "Port Tracer"
date: 2024-03-07
published: true
labels:
  - Python
summary: "Port Tracer is a network security tool designed to identify open ports on a target machine. Using custom-built Python scripts, this tool helps assess potential vulnerabilities in a network by scanning specified IP addresses for open ports. It provides real-time results and enables users to quickly pinpoint weaknesses in a system’s security, making it an essential part of any penetration testing toolkit. The project showcases my ability to work with networking protocols, socket programming, and network security principles."
---

<img class="img-fluid" src="../img/port_tracer/port_tracer-header.png">

Port Tracer is a lightweight yet powerful network security tool designed to help identify open ports on a target machine. It enables users to analyze network security by scanning for potential vulnerabilities.

To give you an idea of how it works, here’s an overview of the process:

<hr>

<pre>
Enter the target IP address:
> 192.168.1.1

Enter the range of ports to scan (e.g., 20-1000):
> 20-1000

Scanning in progress...
Port 22 is open (SSH)
Port 80 is open (HTTP)
Port 443 is open (HTTPS)

Scan complete. Total open ports: 3.
</pre>

<hr>

### How It Works:
1. **User Input** – The user specifies the target IP address and the range of ports to scan.  
2. **Connection Attempts** – The script systematically tries to connect to each port using Python’s `socket` library.  
3. **Response Analysis** – If a connection is successful, the port is marked as open; otherwise, it is considered closed or filtered.  
4. **Results Display** – Open ports are displayed in real time, helping users assess security risks.  

Source: <a href="https://github.com/yourusername/port-tracer"><i class="large github icon "></i>yourusername/port-tracer</a>
