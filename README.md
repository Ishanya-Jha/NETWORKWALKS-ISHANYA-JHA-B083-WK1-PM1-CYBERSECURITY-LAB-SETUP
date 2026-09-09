#🔐 Cybersecurity Lab Environment Setup

NetworkWalks Cybersecurity Internship | Week 1

A practical cybersecurity lab environment built using VirtualBox and Kali Linux. This project focuses on creating a controlled environment for cybersecurity and networking practice, configuring virtual networking, and verifying connectivity and essential security tools.

---

##🎯 Project Objectives

- Set up a cybersecurity lab using VirtualBox
- Configure a NAT Network
- Connect Kali Linux to the virtual network
- Verify network connectivity
- Verify DNS resolution
- Verify Nmap installation
- Troubleshoot basic networking issues
- Document the completed lab environment

---

##⚙️ Lab Environment

Component| Configuration
Virtualization Platform| VirtualBox 7.2.16
Operating System| Kali Linux
Network Mode| NAT Network
Network Range| "10.0.0.0/24"
Purpose| Cybersecurity & Networking Practice

---

##🖥️ NAT Network Configuration

A NAT Network was created in VirtualBox and configured with the required "10.0.0.0/24" network range.

"NAT Network Configuration" (./01-NAT-Network-Configuration.png)

---

##🐉 Kali Linux Virtual Machine

Kali Linux was configured as the primary cybersecurity virtual machine and connected to the NAT Network.

"Kali Linux Virtual Machine" (./02-Kali-Linux-VM.png)

---

##🌐 Network Connectivity Verification

Network connectivity was tested from Kali Linux using:

ping -c 4 8.8.8.8

The final connectivity test completed successfully with 0% packet loss.

"Network Connectivity Test" (./03-Network-Connectivity-Ping.png)

---

##🔎 DNS Resolution Verification

DNS resolution was tested using:

nslookup google.com

The command successfully resolved the domain name.

"DNS Verification" (./05-DNS-Verification.png)

---

##🛡️ Nmap Verification

Nmap installation was verified using:

nmap --version

The command successfully displayed the installed Nmap version.

"Nmap Version" (./04-Nmap-Version.png)

---

##🐞 Troubleshooting Experience

NAT Network Configuration

Problem: The NAT Network was initially created with a different default network range.

Solution: The network configuration was changed to the required "10.0.0.0/24" range.

Network Adapter Configuration

Problem: The network adapter could not initially be enabled while the Kali Linux virtual machine was running.

Solution: The virtual machine was powered off, after which the network adapter could be enabled and configured correctly.

Finding Network Settings

Problem: Initially, the Network settings were not immediately visible in the VirtualBox interface.

Solution: The VirtualBox settings were checked and the Network section was located and configured.

---

#📚 Skills & Knowledge Gained

This project provided practical experience with:

- VirtualBox virtual machine management
- NAT Network configuration
- Kali Linux lab setup
- Network connectivity testing
- DNS verification
- Nmap verification
- Basic network troubleshooting
- Cybersecurity lab documentation

---

##🔐 Security & Ethical Use

This laboratory environment is intended for educational and authorized cybersecurity practice.

All cybersecurity testing should only be performed on systems and networks that are owned by the tester or where explicit permission has been provided.

---

##👤 Project Details

Student: Ishanya Jha
Internship: NetworkWalks Cybersecurity Internship
Week: 1
Project: Cybersecurity Lab Environment Setup

---

📸 Project Evidence

The screenshots in this repository document the major configuration and verification stages completed during the project.
