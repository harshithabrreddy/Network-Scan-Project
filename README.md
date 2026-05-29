# Network Scan Project

## Objective

The objective of this project is to perform local network scanning using Nmap and analyze captured packets using Wireshark.

## Tools Used

* Kali Linux
* Nmap
* Wireshark
* VMware

## Commands Used

```bash
sudo nmap -sS 192.168.93.0/24
```

```bash
sudo nmap -sV -O 192.168.93.0/24
```

## Findings

* Multiple active hosts were identified in the local network.
* Open ports and running services were discovered.
* Apache HTTP server was detected on port 80.
* Windows and Linux operating systems were identified.
* Wireshark captured TCP SYN, ACK, ARP, and retransmission packets.

## Security Risks

* Open HTTP service may expose unencrypted traffic.
* Open ports can increase attack surface.
* Improperly secured services may be vulnerable to attacks.

## Conclusion

This project helped in understanding network reconnaissance, TCP SYN scanning, service enumeration, operating system detection, and packet analysis using Wireshark.
