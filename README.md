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

## Results.txt
<img width="1920" height="1080" alt="Screenshot (196)" src="https://github.com/user-attachments/assets/19f08d57-cba8-4c8c-aaa3-a5dc76a78a97" />
<img width="1920" height="1080" alt="Screenshot (195)" src="https://github.com/user-attachments/assets/7b28702a-2c0f-4c41-afec-8b9e079e38bd" />
<img width="1920" height="1080" alt="Screenshot (194)" src="https://github.com/user-attachments/assets/324c0b1f-0342-4fdb-949b-cbf59de2fa25" />
<img width="1920" height="1080" alt="Screenshot (197)" src="https://github.com/user-attachments/assets/212750d1-8fc7-4a4a-8807-cd8ed2f20c24" />

## Conclusion

This project helped in understanding network reconnaissance, TCP SYN scanning, service enumeration, operating system detection, and packet analysis using Wireshark.
