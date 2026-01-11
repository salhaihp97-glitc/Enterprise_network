# Enterprise_network
in this folder we have all configure for network in GNS3

Abstract
This project addressed the conceptual design and implementation of an advanced enterprise security network using the GNS3 simulation software with VMware support for virtual machines such as pfSense and LibreNMS. The network was segmented into multiple sections (IT, Finance, HR, Administration, and Guest) using independent virtual networks (VLANs) to completely isolate traffic between the security sections on the specialized second technology.

Software-based routing (OSPF) with Inter-VLAN Routing was implemented via SVI interfaces, and IP addresses were automatically allocated via DHCP with protection against DHCP Rogue attacks using DHCP Snooping. Advanced second security was further enhanced by enabling Port Security, Dynamic ARP Inspection (DAI), and Spanning Tree Protocol (STP) to prevent loopholes.

An advanced firewall (pfSense) with NAT rules and a strict firewall, an Intrusion Documentation System (IDS) using Snort, and a centralized system (LibreNMS) with Syslog logging and real-time alerts were also added. Centralized services (DNS, Web Server, FTP, Mail Server, AAA) with Access Control Lists (ACLs) for cross-departmental traffic management and VPN support for remote access were selected.

The project aims to provide a comprehensive, cost-effective, open-source solution incorporating Cisco's global best practices while focusing on the local context in Syria, where the number of cyber users has increased significantly, resulting in a diverse and varied network landscape.
