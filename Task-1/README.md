# 🛡️ Task 1: Scan Your Local Network for Open Ports \[August 04, 2025]

## ✅ Task(s) Assigned

* Learn to discover open ports on devices in your local network to understand network exposure.

## ⚙️ Tools & Technologies Used

* Nmap (free), Wireshark (optional).

## 🔍 Steps Taken / Work Done

1. Figured out my local IP range (i.e. 10.230.171.90/24)

2. Ran nmap scan (i.e. nmap -T4 -A -p- 10.230.171.90/24)

3. Found out the following IP addresses in my local network with ports running on them... (10.230.171.15, 10.230.171.50, 10.230.171.124)

4. Analyzed captured packets with wireshark

5. The common services running on those ports were 

     Port: 80 Service: http

     Port: 6646 Service: tcpwrapped

     Port: 7680 Service: pando-pub?

     Port: 53 Service: tcp

6. Saved Nmap Scan result as nmap\_*scan and Wireshark scan result as wireshark*\_scan

## 📖 Key Learnings

* Basic network reconnaissance skills; understanding network service exposure

## 📎 Resources Referenced

* Wireshark Tutorial - [https://youtu.be/a\_4MjV\_-7Sw?si=29-HidcaUpc\_B8L7](https://youtu.be/a_4MjV_-7Sw?si=29-HidcaUpc_B8L7)

## ⚠️ Challenges & Solutions

* Analyzing the captured packets in wireshark was quite challenging but after taking a look into the youtube tutorial of wireshark (link given above in resources) It solved my problem and enhanced my knowledge.

## 🏁 Status

* ✅ Task completed successfully

## 📝 Key Concepts

* Port scanning, TCP SYN scan, IP ranges, network reconnaissance, open ports,

  network security basics
