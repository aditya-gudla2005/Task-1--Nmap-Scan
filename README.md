# Task-1--Nmap-Scan

## ->Overview

In this task, I performed a basic network reconnaissance to identify live active devices and open TCP ports within my local network using Nmap tool. This exercise helped me understand how port scanning works and how services on a network may expose potential security risks.

## ->Environment

- **Operating System**: Kali Linux (running in virtual environment called VMware)
- **Network Mode**: NAT 
- **Tool Used**: Nmap

## Commands Used
1) ip a (to check my local network ip address)
2) nmap -sS 192.168.124.0/24 -oN scan_output.txt  (for port scanning)
