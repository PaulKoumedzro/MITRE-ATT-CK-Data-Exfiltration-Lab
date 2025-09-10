# Password-Security-Authentication-Hardening-Lab

# Objective

# Skills Learned

# Tools Used
- WireShark
- Windows
- MITRE ATT&CK Framework
# Steps

Fig1: When examining the Protocol Hierarchy in Wireshark, noticed the presence of protocols such as SMB, DNS, HTTPS, and ICMP, which are commonly leveraged by attackers as techniques for data exfiltration.
![1](https://github.com/user-attachments/assets/a158b3cd-0e4c-4d5f-80fb-27fa5538eb2a)

Figure2: After examined the communication between devices by analyzing IP traffic. After sorting the conversations by packet count, it was observed that these top 8 IP addresses exchanged the highest number of packets, indicating a significant volume of data transfer between them. 
![2](https://github.com/user-attachments/assets/05b62723-2c11-4a59-9442-435de4c00330)

Figure3: OSINT is perform on the  the destination IP 184.150.49.96 as shown on the screenshot below.
![Untitled](https://github.com/user-attachments/assets/a7526d68-3224-4dc3-af67-772364d92728)

Fig4: Filtered the IP address 184.150.49.96 using the ip.addr==184.150.49.16 and followed the HTTP stream. Again the address is benign and is related to microsft[.]com
![3](https://github.com/user-attachments/assets/20431e48-1719-4cfe-8300-99380e5bb485)

Fig5: Let's Perform OSINT on the second destination IP address 192.168.100.101 (external)
![4](https://github.com/user-attachments/assets/3414d429-c2f3-4da2-8338-b6f455e67914)

Fig6: Filtered the logs with  the ip.addr==192.168.100.101 and followed the UDP stream. We do see a file named "Passowrd.txt" that has been exfiltrated.
![5](https://github.com/user-attachments/assets/5a8b7d26-0c9b-4b6e-ba08-ca9fb90fcd62)
