# Willian Spohr – Cybersecurity Portfolio

## Overview

This repository contains my hands-on cybersecurity labs performed in a controlled virtual lab environment using Kali Linux and Ubuntu.

The purpose of this portfolio is to develop practical skills in penetration testing, network scanning, and system enumeration.

---

## Lab Environment

Attacker Machine:
- Kali Linux
- IP: 192.168.56.104

Target Machine:
- Ubuntu Linux
- IP: 192.168.56.103

Network:
- VirtualBox Host-only Adapter
- Network range: 192.168.56.0/24

---

## Tools Used

- Nmap
- Kali Linux
- Ubuntu Linux
- VirtualBox
- Linux command line

---

## Labs Completed

### Network Scanning Lab

Objectives:
- Host discovery
- Port scanning
- Service detection
- OS detection

Command used:

sudo nmap -sS -sV -O -p- 192.168.56.103

Result:

PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 9.6p1 Ubuntu

Skills demonstrated:

Network scanning

Service enumeration

Linux networking

Lab environment configuration

Skills Developed

TCP/IP networking fundamentals

Port scanning methodology

Linux system usage

Cybersecurity lab setup

Current Learning Goals

Service enumeration

Linux enumeration

Vulnerability analysis

Penetration testing

## Portfolio Projects

### Network Scanning Lab

A practical lab using **Nmap** to identify open ports and services on a target machine in a virtual lab.

- 🛠️ Tools used: Kali Linux, Ubuntu, Nmap, VirtualBox
- 🔍 Skills: Port scanning, service enumeration, OS detection

🔗 [View Lab →](./network-scanning-lab)

Disclaimer

All activities were performed in a controlled virtual lab environment for educational purposes only.
