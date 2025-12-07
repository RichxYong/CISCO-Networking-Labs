**01-WIRELESS-ROUTER-LAB**
---


📋 **LAB OVERVIEW**
---
Helping Natsumi connect her new home to the cable TV network and set up a complete home wireless network including cable connections, router configuration, DHCP setup, and wireless LAN configuration.


🎯 **OBJECTIVES**
---
✅ Connect correct cables between cable TV network and home devices

✅ Configure home wireless router with proper settings

✅ Implement DHCP server for automatic IP address assignment

✅ Setup secure wireless LAN (WLAN) for home devices

✅ Verify network connectivity for all devices


✅**WHAT I ACHIEVED**
---
Successfully established  TV cable connection to the home

Properly configured the wireless router with DHCP enabled

Created a secure wireless network with WPA2 encryption

Verified connectivity for both wired and wireless devices

Ensured all devices receive IP addresses automatically


🛠️ **HOW i DID IT**
---
**Step 1: Physical Cable Connections**
Connected coaxial cable from wall outlet to cable modem

Connected Ethernet cable from modem to router's WAN port

Connected desktop computer to router's LAN port 1

Connected laptop wirelessly to the router

Connected cable TV set-top box to cable modem

**Step 2: Router Configuration**
Accessed router interface:

Opened web browser and navigated to 192.168.1.1

Logged in with default credentials (user:admin  pasword:admin)

Configured WAN settings for DHCP from ISP

Enabled DHCP server on router:

IP Pool: 192.168.1.100 to 192.168.1.200

Subnet Mask: 255.255.255.0

Default Gateway: 192.168.1.1

DNS Servers: ISP provided

**Step 3: Wireless LAN Setup**
Configured wireless settings:

**Step 4: Device Configuration**
Desktop Computer (Wired):

Set to obtain IP address automatically (DHCP)

Verified connectivity to router and internet

Laptop (Wireless):

Connected to "Myhome" wireless network

Entered WPA2 password

Confirmed IP address received via DHCP

**Step 5: Verification and Testing**
# On Desktop (Command Prompt):
ipconfig /all
ping 192.168.1.1
ping 8.8.8.8
ping www.google.com

📁 **FILES INCLUDED**
---
Configutre a Wireless Router and Client Labwork.pkt - Main Packet Tracer file

Wireless Router and Client.pdf - Configuration Notes/guide

Screenshots of Lab Work folder - Contains screenshots of the Labwork
***

🖥️ **HOW TO VIEW THIS LAB ON YOUR PC**
---
**Requirements:**
Cisco Packet Tracer 8.x or newer

Basic understanding of home networking concepts

**Steps to Open:**
Install Cisco Packet Tracer (if not already installed)

Available to Cisco Networking Academy students

Or download public version from Cisco's website

Clone or Download this Lab:

Launch Cisco Packet Tracer

Click File → Open

Navigate to and select wireless router.pkt

**Explore the Lab:**

Click on the wireless router to view configurations

Check device IP addresses with ipconfig or GUI

Test connectivity between devices

Examine wireless settings


***
