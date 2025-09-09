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

Figure2: After examined the communication between devices by analyzing IP traffic. After sorting the conversations by packet count, it was observed that IP addresses 192.168.100.200 and 184.150.49.96 exchanged the highest number of packets, indicating a significant volume of data transfer between them. 
![Screenshot 2025-09-09 182814](https://github.com/user-attachments/assets/c4b52fc6-75a1-4db3-bf28-69f222f81628)


Figure3: John The Ripper is used to crack the md5 hash we identified earlier  stored in a text file called passwd.txt
![Untitled](https://github.com/user-attachments/assets/a7526d68-3224-4dc3-af67-772364d92728)

# Password Security and Authentication Hardening Recommendations.

- Always Use Complex and long password. At least 16 characters long,combination of Special characters. Never use anything or name associate with you as password. Complex passwords are difficult for attacker to crack.
- Avoid using dictionary words or pre computed words.
- Change your passwords regurlary at least every 6 months.
- Always use Mutli  Factor Authentication to add one extra layer of protection to your account.
- Keep You applications Up to date.
