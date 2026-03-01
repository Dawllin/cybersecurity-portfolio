# Network Scanning Lab – Nmap

## Objective

Perform network scanning and identify open ports and services on a target machine using Nmap.

---

## Lab Environment

Attacker Machine:

* Kali Linux
* IP: 192.168.56.104

Target Machine:

* Ubuntu Linux
* IP: 192.168.56.103

Network:

* VirtualBox Host-only Adapter
* Range: 192.168.56.0/24

---

## Command Used

```bash
sudo nmap -sS -sV -O -p- 192.168.56.103
```

---

## Scan Result

```
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 9.6p1 Ubuntu
```

---

## Analysis

The scan identified that port 22 is open and running SSH.

This indicates:

* The host is active
* SSH service is running
* Service version was detected
* Target OS is Linux

---

## Skills Demonstrated

* Network scanning
* Port enumeration
* Service detection
* OS fingerprinting
* Virtual lab configuration

---

## Conclusion

This lab demonstrates how to identify open ports and services using Nmap in a controlled cybersecurity lab environment.
