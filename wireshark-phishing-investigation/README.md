# Wireshark Phishing Investigation

## Overview

This project documents a simulated Business Email Compromise (BEC) investigation. Using Wireshark, I analyzed packet capture (PCAP) files containing SMTP traffic to investigate suspicious email activity and practice identifying phishing emails through network traffic analysis.

## Objectives

* Analyze PCAP files using Wireshark.
* Filter SMTP traffic to investigate email communications.
* Differentiate legitimate emails from phishing emails.
* Examine SMTP headers and packet metadata.
* Practice documenting a cybersecurity investigation.

## Scenario

In this simulated investigation, a company suspected a Business Email Compromise (BEC) attack after employees received suspicious emails. My task was to analyze the provided PCAP files, identify phishing activity, and investigate the origin of the malicious email campaign using Wireshark.

## Tools

* Wireshark
* PCAP Files
* SMTP Protocol
* Virtual Machine (VM)
* Linux Terminal

## Process

1. Accessed the virtual machine environment and downloaded the provided PCAP files.
2. Extracted the files and opened each capture individually in Wireshark.
3. Applied display filters such as `smtp` to isolate email traffic.
4. Used additional filters, including `smtp contains "FROM"` and `smtp.data.fragment`, to examine email communications and subject lines.
5. Compared the SMTP traffic across the PCAP files to identify suspicious activity.
6. Reviewed SMTP metadata and packet details to investigate the simulated phishing campaign.

## Skills

* Wireshark
* Packet Capture (PCAP) Analysis
* Network Traffic Analysis
* SMTP Analysis
* Email Header Analysis
* Phishing Investigation
* Indicator of Compromise (IOC) Identification
* Technical Documentation

## Screenshots

> Add screenshots of your investigation here, such as:
>
> * Opening a PCAP file in Wireshark
> * Applying the `smtp` display filter
> * Examining SMTP packet details
> * Reviewing email header information
>
> Include a short caption below each screenshot explaining what it shows.

## Lessons Learned

This project strengthened my understanding of network packet analysis and phishing investigations. I learned how Wireshark can be used to inspect SMTP traffic, analyze email metadata, and support a structured investigation. I also became more comfortable navigating a virtual machine environment and using display filters to efficiently locate relevant network traffic.

## References

This project was completed as part of the CodePath Intermediate Cybersecurity course using a simulated phishing scenario. The documentation in this repository reflects my own understanding of the investigation process and the techniques used during the lab.
