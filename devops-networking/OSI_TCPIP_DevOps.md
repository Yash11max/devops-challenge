Understanding OSI & TCP/IP Models in DevOps

Introduction

In the world of DevOps, understanding networking fundamentals is crucial for managing infrastructure, automating deployments, and ensuring system security. Two key models help us conceptualize how data moves across networks: the OSI and TCP/IP models. Additionally, knowing the most commonly used protocols and their ports allows DevOps engineers to configure secure and efficient workflows.

In this blog, we will break down these models with real-world examples and explore essential protocols used in DevOps.

Here’s how each layer applies to real-world scenarios:

1. Application Layer (Layer 7)

Example: A user accesses a website using a web browser. The browser sends an HTTP request to the server.

Common Protocols: HTTP, HTTPS, FTP, SMTP, DNS

2. Presentation Layer (Layer 6)

Example: A web server encrypts data using SSL/TLS before sending it over HTTPS.

Common Functions: Data encryption, compression, encoding (e.g., JPEG, MP3, TLS)

3. Session Layer (Layer 5)

Example: A user logs into an SSH session to manage a remote server.

Common Functions: Session establishment and termination (e.g., NetBIOS, RPC, SOCKS)

4. Transport Layer (Layer 4)

Example: TCP ensures that all packets of a large file download arrive in order and without corruption.

Common Protocols: TCP, UDP

5. Network Layer (Layer 3)

Example: A router forwards packets based on IP addresses to reach the correct destination.

Common Protocols: IP, ICMP, ARP

6. Data Link Layer (Layer 2)

Example: A switch directs data frames within a local network using MAC addresses.

Common Protocols: Ethernet, Wi-Fi (IEEE 802.11), PPP

7. Physical Layer (Layer 1)

Example: A network cable transmits electrical signals between a computer and a switch.

Common Media: Ethernet cables, fiber optics, radio waves

TCP/IP Model

The TCP/IP model is a more practical and widely used framework for real-world networking. It consists of four layers:

Application Layer - Merges OSI Layers 5-7 (HTTP, DNS, SMTP)

Transport Layer - Corresponds to OSI Layer 4 (TCP, UDP)

Internet Layer - Corresponds to OSI Layer 3 (IP, ICMP, ARP)

Network Access Layer - Merges OSI Layers 1-2 (Ethernet, Wi-Fi)

