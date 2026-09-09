🔐 Cybersecurity Lab Environment Setup

📌 Project Overview

This project is part of my Week 1 Cybersecurity Internship at NetworkWalks.

The objective of this project was to set up a basic cybersecurity lab environment using VirtualBox and Kali Linux. The lab provides an environment for practicing cybersecurity and networking concepts safely.

🎯 Objectives

- Set up a virtual cybersecurity lab
- Configure VirtualBox for the lab environment
- Create and configure a NAT Network
- Connect Kali Linux to the virtual network
- Verify network connectivity
- Verify DNS resolution
- Verify Nmap installation
- Document the lab setup using screenshots

⚙️ Lab Environment

Component| Configuration
Virtualization Software| VirtualBox 7.2.16
Operating System| Kali Linux
Network Type| NAT Network
Network Range| 10.0.0.0/24

«Private IP addresses from my individual machine are not included in this public repository.»

🛠️ Lab Setup

1. NAT Network Configuration

A NAT Network was created in VirtualBox and configured with the required "10.0.0.0/24" network range.

"NAT Network Configuration" (01-NAT-Network-Configuration.png)

2. Kali Linux Virtual Machine

Kali Linux was configured as the primary cybersecurity virtual machine and connected to the NAT Network.

"Kali Linux VM" (02-Kali-Linux-VM.png)

3. Network Connectivity Verification

Network connectivity was tested from Kali Linux using:

ping -c 4 8.8.8.8

The final connectivity test was successful with 0% packet loss.

"Network Connectivity Ping" (03-Network-Connectivity-Ping.png)

4. DNS Verification

DNS resolution was tested using:

nslookup google.com

The test successfully resolved the domain name.

"DNS Verification" (05-DNS-Verification.png)

5. Nmap Verification

Nmap installation was verified using:

nmap --version

The command successfully displayed the installed Nmap version.

"Nmap Version" (04-Nmap-Version.png)

🐞 Troubleshooting Experience

During the setup, I encountered a few configuration issues.

Issue 1: NAT Network Configuration

The NAT Network was initially created with a different default network range.

Solution:
I changed the NAT Network configuration to the required "10.0.0.0/24" range.

Issue 2: Network Adapter Configuration

The network adapter could not initially be enabled because the Kali Linux virtual machine was running.

Solution:
I powered off the virtual machine and then enabled and configured the network adapter.

Issue 3: Finding Network Settings

Initially, I had difficulty locating the Network settings in the VirtualBox interface.

Solution:
I explored the VirtualBox settings and located the Network section, where I configured the NAT Network.

💡 What I Learned

Through this project, I learned how to:

- Create and configure a NAT Network in VirtualBox
- Connect a Kali Linux virtual machine to a virtual network
- Test network connectivity
- Verify DNS resolution
- Verify Nmap installation
- Troubleshoot basic VirtualBox networking issues
- Document a cybersecurity lab environment

🔐 Security & Ethical Use

This lab is intended for educational and authorized cybersecurity practice.

All testing should be performed only on systems and networks that I own or have explicit permission to test.

👤 Project Information

Internship: NetworkWalks Cybersecurity Internship
Week: 1
Project: Cybersecurity Lab Setup
Student: Ishanya Jha
