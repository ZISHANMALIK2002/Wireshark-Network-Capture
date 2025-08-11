# 🎯 Capture live packets on your network, identify at least three different protocols, and export the capture.

## 🖥 Step 1: Install Wireshark
- Download from: https://www.wireshark.org/download.html
- Install with default settings (enable npcap if prompted — it’s needed for capturing packets).

  ## 🖥 Step 2: Start Capturing Traffic
  - Open Wireshark.
  - Select your active network interface (e.g., Wi-Fi, Ethernet).
  - Click the blue shark fin icon (Start Capture).
 
  ## 🖥 Step 3: Generate Network Activity
  While Wireshark is capturing:
  - Open a browser and visit some websites (e.g., example.com, google.com).
  - Optionally, ping a server: ping google.com


 ## 🖥 Step 4: Stop the Capture
 - After about 1 minute, click the red square (Stop Capture).


## 🖥 Step 5: Filter by Protocol
In the top filter bar, try:
- http → shows web traffic
- dns → shows domain lookups
- tcp or udp → shows transport layer packets

## 🖥 Step 6: Identify at least 3 Protocols
For example:
- HTTP → Web requests
- DNS → Resolving domain names
- TCP → Reliable data transport
- ICMP → Ping messages

## 🖥 Step 7: Export the Capture
- Go to File → Save As
- Choose .pcapng format
- Save as network_capture.pcapng
