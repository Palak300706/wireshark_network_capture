Capture Network Traffic with Wireshark

Introduction

Wireshark is a network protocol analyzer used to capture and inspect network packets in real time. It helps analyze network communication, troubleshoot issues, and understand how data travels across networks.

This project demonstrates capturing and analyzing HTTP network traffic using Wireshark in Kali Linux.

Objective

The objective of this task is to:
- Install Wireshark
- Capture local network traffic
- Filter HTTP packets
- Analyze captured network packets

Tool Used

- Wireshark

Steps Performed

1. Installed Wireshark on Kali Linux.

2. Started packet capture on the active network interface.

3. Generated HTTP traffic by visiting websites.

4. Applied HTTP filter in Wireshark.

5. Analyzed captured packets.

6. Saved the packet capture file as:
   wireshark_capture.pcap

HTTP Filter Used

http

Explanation of Captured Packets

The captured packets included:

* HTTP GET requests
* Source and destination IP addresses
* Packet sizes
* Communication between client and server

Packet Analysis

1. Source IP Address

The source IP represents the sender device initiating the request.

2. Destination IP Address

The destination IP represents the web server receiving the request.

3. HTTP GET Request

HTTP GET requests are used by browsers to request web pages from servers.

4. Protocol Information

The protocol field identifies the communication protocol used, such as HTTP or TCP.

5. Packet Length

Packet length shows the size of transmitted network data.

Importance of Packet Analysis

Network packet analysis helps:

* Monitor network activity
* Detect suspicious traffic
* Troubleshoot network issues
* Understand communication between devices
* Improve cybersecurity monitoring

Conclusion

This project successfully demonstrated network traffic capture and analysis using Wireshark. The captured HTTP packets provided insight into how devices communicate over a network and highlighted the importance of packet analysis in cybersecurity and network administration.
