# NETWORKWALKS-B084A-WK2-FOOTPRINTING-AND-ZENMAP
# Week 2 – Footprinting \& Network Scanning 

### Network Walks Cybersecurity Internship

## 1. Project Overview

As part of Week 2 of my NetworkWalks Cybersecurity Internship, I completed practical exercises on Footprinting and Network Scanning using Kali Linux and Zenmap.

The main objective was to understand how information about a target website can be collected using footprinting tools and how live devices can be identified within an authorised local network.

This project helped me gain practical experience with information gathering, network discovery, interpreting scan results and documenting technical findings.

## 2. Objectives

- Understand the basics of footprinting and information gathering.
- Explore website and DNS information using Kali Linux tools.
- Identify web technologies and security-related information.
- Discover live hosts within my local network.
- Observe IP and MAC address information where available.
- Generate and save a network topology diagram.
- Document the activities and findings.

## 3. Modules Completed

| Module | Project | Status |
| --- | --- | --- |
| W2-PM1 | Footprinting | Completed |
| W2-PM5 | Network Scanning with Zenmap | Completed |
| W2-PM-FINAL | Final Report | Completed |

## 4. Tools Used

### A. Footprinting – Kali Linux

The following six tools were used during the footprinting exercise:

1. WHOIS – Collected domain registration information.
2. WhatWeb – Identified technologies used by the target website.
3. Nslookup – Retrieved DNS information.
4. cURL – Examined HTTP responses and website headers.
5. WAFW00F – Checked for the presence of a Web Application Firewall.
6. DNSRecon – Gathered DNS records and related information.

### B. Network Scanning – Zenmap

Zenmap (Nmap GUI)** was used to perform a ping scan and identify live hosts in the local network.

- Scan profile: Ping Scan
- Scan command: `nmap -sn 10.227.168.0/24`
- Network subnet: `10.227.168.0/24`

## 5. Methodology and Activities

### Module 1 – Footprinting

I performed information gathering against the assigned target, `networkwalks.com`, using six Kali Linux tools.

The activities included:

- Checking domain registration details.
- Identifying website technologies.
- Looking up DNS information.
- Examining HTTP response headers.
- Checking for WAF presence.
- Enumerating available DNS records.

The collected outputs and screenshots were saved as project evidence.

### Module 2 – Network Scanning with Zenmap

I installed Zenmap on my Windows laptop and used the Ping Scan profile to discover live hosts in my local network.

The scan covered 256 IP addresses in the `10.227.168.0/24` subnet.

Scan result:

- Total IP addresses scanned: 256
- Live hosts discovered: 2
- Scan duration: Approximately 10.26 seconds

### Identified Live Hosts

| No. | IP Address | Observation |
| --- | --- | --- |
| 1 | 10.227.168.29 | Gateway / network device |
| 2 | 10.227.168.115 | My Windows laptop |

The scan identified two live hosts. MAC address information was available for the gateway in the Zenmap output. The Windows laptop's Wi-Fi MAC address was checked separately using Windows network configuration.

## 6. Results and Findings

The footprinting exercise provided practical exposure to domain information, DNS records, website technologies, HTTP responses and WAF detection.

The Zenmap exercise successfully identified two live hosts in the scanned local subnet and generated a network topology view.

The results demonstrate how footprinting and basic network discovery can support the initial stages of a cybersecurity assessment.

## 7. Project Evidence

The repository contains the following supporting evidence:

- Footprinting screenshots for all six tools.
- Saved footprinting command outputs.
- Footprinting project report.
- Zenmap scan output screenshot.
- Local IP and network configuration evidence.
- Network topology screenshot.
- Saved Zenmap topology PDF.

## 8. Learning Outcomes

Through these practical exercises, I gained experience in:

- Using common information-gathering tools in Kali Linux.
- Understanding domain and DNS information.
- Examining HTTP response information.
- Recognising WAF detection results.
- Understanding IP addresses and subnet notation.
- Using Zenmap for local network discovery.
- Reading scan results and identifying live hosts.
- Documenting technical activities and findings.

## 9. Conclusion

Week 2 gave me an opportunity to apply basic cybersecurity concepts through practical exercises rather than theory alone.

Completing the footprinting and network scanning modules improved my understanding of information gathering, network discovery and technical documentation.

I also learned the importance of interpreting results carefully and performing testing only within an authorised scope.

---

Internship: NetworkWalks Cybersecurity Internship  
Project: Week 2 – Footprinting \& Network Scanning  
Status: Completed
