# Suricata Network Intrusion Detection System (IDS)

## Project Overview

This project demonstrates the deployment and configuration of a Network-based Intrusion Detection System (NIDS) using **Suricata**.  
The system detects common network attacks and suspicious activity and automatically blocks malicious IP addresses.

## Environment

* Attacker: Kali Linux
* Victim / IDS: Lubuntu
* IDS Engine: Suricata 8.0.2
* Network Mode: Bridged Adapter

## Features

* Real-time traffic inspection
* Emerging Threats rule set
* Custom Suricata rules
* Detection of ICMP, Nmap scans, and SSH brute-force attempts
* Automatic IP blocking using iptables
* Alert logging via fast.log

## \## Detection Examples

## 

## \### ICMP Detection

## !\[ICMP Alert](screenshots/icmp\_alert.png)

## 

## \### Nmap Scan Detection

## !\[Nmap Alert](screenshots/nmap\_alert.png)

## 

## \### SSH Brute-force Detection

## !\[SSH Alert](screenshots/ssh\_bruteforce\_blocked.png)

## 

## \### Blocked Attacker (iptables)

## !\[iptables](screenshots/iptables\_block.png)

## 

## \## Conclusion

## This project successfully demonstrates how Suricata can be used to detect and respond to network attacks in real time.  

## Visualization dashboards were considered optional, and analysis was performed directly using Suricata log files.

## 

## \## Author

## \- Name: YOUR NAME

## \- Field: Cybersecurity /

