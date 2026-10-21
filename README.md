# Network Packet Sniffer Using Python

## Overview
This project was completed as part of my Prodigy InfoTech cybersecurity internship. It demonstrates how Python can be used to capture and inspect network packets for educational network monitoring and analysis.

The project introduces basic packet analysis and helps develop an understanding of network communication.

## Objectives
- Understand the fundamentals of network packet analysis.
- Explore packet capture using Python.
- Learn how network traffic can be inspected.
- Understand the role of packet analysis in cybersecurity monitoring.

## Technologies Used
- Python 3
- Scapy (if used in the implementation)

## Features
- Captures network packets using the implemented packet-capture method.
- Displays packet information available to the program.
- Demonstrates basic network traffic inspection.
- Supports learning about network communication protocols.

## How It Works
1. The program starts packet capture on the configured network interface or through the capture method used in the code.
2. Network packets are collected according to the configured capture settings.
3. The program processes the captured packets.
4. Available packet details are displayed for inspection.

The protocols and fields displayed depend on the implementation.

## Prerequisites
- Python 3 installed on your system.
- Required packet-capture library installed, if applicable.
- Appropriate permissions to capture traffic on the selected interface.

## Installation

Clone the repository:

```bash
git clone https://github.com/racheljo11/python-packet-sniffer.git
```

Navigate to the project directory:

```bash
cd python-packet-sniffer
```

If the code uses Scapy, install it with:

```bash
python -m pip install scapy
```

## How to Run

Run the Python script using its actual filename:

```bash
python filename.py
```

Replace `filename.py` with the name of your Python script.

Depending on your operating system and capture method, elevated permissions or additional packet-capture components may be required.

## Results
The program displays information from captured packets according to its implementation.

Add a screenshot
