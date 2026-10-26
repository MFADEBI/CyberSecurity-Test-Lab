Cybersecurity-Test-Lab
Project Overview

This project documents my hands-on setup of a Kali Linux virtual machine using Oracle VirtualBox as part of my cybersecurity learning journey.
The goal was to configure a dedicated lab environment with reliable network connectivity and essential virtual machine integration features.
 Lab Configuration- Operating System: Kali Linux
Virtualization Platform: Oracle VirtualBox
Network Mode: NAT Network
NAT Network Subnet: 10.0.0.0/24
Kali Linux IP Address: 10.0.0.2/24
DNS Server: Google Public DNS - 8.8.8.8

 Tasks Completed
 
Configured a VirtualBox NAT Network.
Configured and verified the required Kali Linux IP address.
Tested internet connectivity and DNS resolution (changed DNS default from 1.1.1.1 to 8.8.8.8 Public)
Enabled bidirectional shared clipboard and drag-and-drop.
Configured a shared Windows Downloads folder accessible from Kali Linux.
Used Linux terminal commands to inspect network configuration and troubleshoot connectivity.

Screenshots and Evidence
1. Kali Linux IP Configuration
   
2. DNS Configuration Google Public DNS Configuration

3. Shared Windows Downloads Folder Shared Downloads Folder


Commands Used

Check the IP address: ip -br address

Inspect DNS configuration: nmcli device show eth0 | grep IP4.DNS

Test internet connectivity: ping -c 4 1.1.1.1

Test DNS resolution: getent hosts google.com

Access the shared folder: ls /media/sf_Downloads

Skills Practiced

- Linux administration
- IP addressing and subnetting
- NAT networking
- DNS configuration
- Network troubleshooting
- Virtual machine integration

## Key Learning
This project improved my practical understanding of Linux networking, DNS configuration, VirtualBox networking, and troubleshooting a virtual cybersecurity lab environment.

Thank you to NETWORKWALKS for the learning opportunity and practical exposure. This exercise has strengthened my understanding of Linux networking and troubleshooting.
I'm looking forward to building on these foundations through more hands-on cybersecurity labs.

## Disclaimer
This repository documents a personal learning lab created for educational and authorized cybersecurity practice.
