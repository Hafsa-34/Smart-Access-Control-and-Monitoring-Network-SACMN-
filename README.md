# Smart-Access-Control-and-Monitoring-Network-SACMN-
This project simulates a secure and intelligent building access control system using Cisco Packet Tracer. It integrates RFID-based authentication with automated responses like door control, alarms, and IoT devices (fan and light) to create a functional and scalable security infrastructure. The setup is designed to demonstrate how IT departments can implement smart access control in enterprise environments.

🎯 Purpose

The primary purpose of this project is to simulate and showcase:

Secure entry management using RFID technology

Automated control of physical infrastructure (doors, alarms, lighting, ventilation)

Event-based IoT responses based on access control conditions

Network design and communication within a smart building or enterprise IT environment

This system can be adapted for offices, labs, schools, or restricted areas, where controlled access and responsive automation are essential for safety and efficiency.

🧠 Key Features

RFID Authentication Logic:

Cards categorized as VALID or UNKNOWN

Valid cards unlock the door and activate devices

Invalid cards trigger an alarm and deny access

Automated Actions:

Devices respond instantly based on card status

Light and fan respond to access status

Alarm system ensures security on unauthorized attempts

Dynamic Network Configuration:

DHCP server assigns IPs automatically

Centralized management via IoT server

Enterprise IT Simulation:

Multiple workstations simulate a realistic IT department scenario

📋 RFID Conditions on the IoT Server

✅ RFID VALID

If RFID card ID matches any of:

1001–1011
→ Action: Set RFID Status to Valid

❌ RFID INVALID

If card ID does not match any valid ID:
→ Action: Set RFID Status to Invalid

🚪 Device Reactions Based on RFID Status

RFID Status	Door	Siren	Light	Fan

Valid	Unlock	Off	Bright	High

Invalid	Lock	On	Dim	Off

Waiting	Lock	Off	Off	Off

🌐 Network Topology Overview

Router – 192.168.1.1

DHCP Server – 192.168.1.2

RFID Reader – 192.168.1.3

Door Lock – 192.168.1.4

Siren – 192.168.1.5

Light – 192.168.1.6

Fan – 192.168.1.7

IT Department – PCs and Laptops for a simulated enterprise environment

🛠 Technologies Used

Cisco Packet Tracer

RFID & IoT Device Simulation

Event-Driven Automation

DHCP, Routing & Switching
