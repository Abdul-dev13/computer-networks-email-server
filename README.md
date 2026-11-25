# Lab 08 — Email Server Configuration and Testing in Cisco Packet Tracer

Course: CSDF 30118 — Computer Networks, 4th Semester
The Islamia University of Bahawalpur — Department of Cyber Security and Digital Forensics
Student: Abdul Ghafoor (S25BINCE1M04017)

## What this lab does

Configure an email server in Cisco Packet Tracer and send an email between two PCs using SMTP and POP3.

## Network

- Server0 — 192.168.1.1 (email server, SMTP and POP3 ON, domain lab.com, users user1 and user2)
- PC0 — 192.168.1.2 (user1@lab.com)
- PC1 — 192.168.1.3 (user2@lab.com)
- All connected to Switch0 (2960-24TT) with Copper Straight-Through cables
- Subnet mask 255.255.255.0, default gateway 192.168.1.1

## Result

- Test email sent from PC0 (user1@lab.com) to PC1 (user2@lab.com) — received, "Receive Mail Success"
- Ping from PC0 to 192.168.1.1 and to 192.168.1.3: 4/4 replies, 0% loss

## Files

- `Lab-08-Email-Server-Configuration-and-Testing.pdf` — full lab report
- `Lab-08-Email-Server-Configuration-and-Testing.docx` — editable Word version
