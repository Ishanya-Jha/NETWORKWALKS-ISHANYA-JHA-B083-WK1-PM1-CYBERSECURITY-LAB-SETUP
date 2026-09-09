🔐 Cybersecurity Lab Environment Setup

NetworkWalks Cybersecurity Internship | Week 1

A practical cybersecurity lab environment built using VirtualBox and Kali Linux. The purpose of this project was to create a controlled virtual environment for cybersecurity and networking practice, configure virtual networking, and verify connectivity and essential security tools.

---

🎯 Project Objectives

The main objectives of this project were:

- Set up a cybersecurity lab using VirtualBox
- Configure a NAT Network for virtual machines
- Connect Kali Linux to the virtual network
- Verify network connectivity
- Verify DNS resolution
- Verify Nmap installation
- Troubleshoot basic VirtualBox networking issues
- Document the complete setup with screenshots

---

⚙️ Lab Environment

Component| Details
Virtualization Platform| VirtualBox 7.2.16
Operating System| Kali Linux
Network Mode| NAT Network
Network Range| "10.0.0.0/24"
Purpose| Cybersecurity & Networking Practice

---

🖥️ VirtualBox NAT Network Configuration

A NAT Network was created in VirtualBox to provide network connectivity for the cybersecurity lab.

The network was configured using the required "10.0.0.0/24" range with DHCP enabled.

"NAT Network Configuration" (./01-NAT-Network-Configuration.png)

---

🐉 Kali Linux Virtual Machine

Kali Linux was used as the primary cybersecurity virtual machine.

The virtual machine was connected to the configured NAT Network so that network connectivity and cybersecurity tools could be tested inside the lab.

"Kali Linux Virtual Machine" (./02-Kali-Linux-VM.png)

---

🌐 Network Connectivity Verification

Network connectivity was tested from Kali Linux using Google's public DNS server:

ping -c 4 8.8.8.8

The final test completed successfully with 0% packet loss, confirming that the Kali Linux virtual machine had working network connectivity.

"Network Connectivity Test" (./03-Network-Connectivity-Ping.png)

---

🔎 DNS Resolution Verification

DNS functionality was tested using:

nslookup google.com

The command successfully resolved the domain name, confirming that DNS resolution was working correctly inside the lab.

"DNS Verification" (./05-DNS-Verification.png)

---

🛡️ Nmap Verification

Nmap is an important network scanning and security assessment tool included in Kali Linux.

Its installation was verified using:

nmap --version

The command successfully displayed the installed Nmap version.

"Nmap Version" (./04-Nmap-Version.png)

---

🐞 Troubleshooting & Solutions

NAT Network had the wrong default range

When the NAT Network was initially created, VirtualBox assigned a different default network range.

Solution:
The network configuration was changed to the required "10.0.0.0/24" range.

Network Adapter could not be enabled

The network adapter could not initially be enabled because the Kali Linux virtual machine was running.

Solution:
The virtual machine was powered off, after which the network adapter could be enabled and configured correctly.

Difficulty locating Network settings

Initially, the Network settings were not immediately visible in the VirtualBox interface.

Solution:
The VirtualBox settings were checked and the Network section was located and configured.

---

📚 Skills & Knowledge Gained

This project provided practical experience with:

- VirtualBox virtual machine management
- NAT Network configuration
- Kali Linux lab setup
- Basic network troubleshooting
- Network connectivity testing
- DNS troubleshooting and verification
- Nmap verification
- Cybersecurity lab documentation
- Safe and authorized cybersecurity practice

---

🔐 Security & Ethical Use

This laboratory is intended strictly for educational and authorized cybersecurity practice.

Security testing should only be performed on systems and networks that are owned by the tester or where explicit permission has been provided.

---

👤 Project Details

Student: Ishanya Jha
Internship: NetworkWalks Cybersecurity Internship
Week: 1
Project: Cybersecurity Lab Environment Setup

---

📸 Project Evidence

The repository contains screenshots documenting the major configuration and verification stages of the cybersecurity lab.

Lab configured successfully. Connectivity verified. Nmap verified. Documentation completed. 🔐
