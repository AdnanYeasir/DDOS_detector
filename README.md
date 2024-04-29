# Deauth Attack Detector

## Overview
The Deauth Attack Detector is a Python-based tool that helps in identifying deauthentication packets in wireless networks. These packets are often used in denial-of-service (DoS) attacks. By monitoring the packet count and types, this tool can help distinguish between normal network behavior and potential DoS attacks.

## Developed By
Adnan Yeasir


## Requirements
- Python 2.7
- Scapy

## Installation
Before running the script, you need to install Scapy, a powerful Python library for packet manipulation. Install Scapy using pip:

bash
pip install scapy


##Usage
-To use the Deauth Attack Detector, follow these steps:

1.Ensure you have the necessary permissions to capture packets on your network interface.
2.Run the script by executing it in a terminal:

``python deauth_attack_detector.py``


Enter the name of your network interface when prompted. The script will start monitoring the traffic on that interface and will print a message whenever a deauthentication packet is detected.
Important Notes
This tool requires administrative or root permissions to read packets from the network interface.
Make sure you are legally allowed to monitor the network in question to avoid any legal issues.
The tool is developed for educational purposes and should not be used for unauthorized network monitoring.
License
This project is licensed under the MIT License - see the LICENSE file for details.


This `README.md` file should be placed in the same directory as your Python script. It provides a comprehensive guide on how to set up, use, and understand the purpose of your tool. If you have any other sections you'd like to add or specific information, feel free to let me know!
