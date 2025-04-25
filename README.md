# Using-Wireshark---analyzing-web-browser-artifacts-email-header-analysis
## AIM:
To use Wireshark to analyze web browser activities and inspect email headers from captured network traffic.

## DESIGN STEPS:
### Step 1:
Launch Wireshark and start capturing traffic on the appropriate network interface.

### Step 2:
Use filters like http, dns, or tcp.port == 80 to monitor web browser artifacts such as visited URLs, cookies, and user-agent strings.

### Step 3:
Apply filters like smtp, pop, or imap to locate and analyze email header details (e.g., sender, receiver, subject) from email communications.

## PROGRAM:
Wireshark Web and Email Traffic Filtering Steps

## OUTPUT:
- Captured Web Activity and Email Header Information

![435733124-f387facb-28db-4353-88ff-70a3f9a3cf07](https://github.com/user-attachments/assets/3c21dabb-14df-4d6c-9426-df2ce42936be)


- ## Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.

![435737551-3b0da9da-047e-45f9-a0bc-ca3a7158b474](https://github.com/user-attachments/assets/43559373-fc9a-41d7-85fb-7a1329ccc0c0)


- ## Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.

![435738301-5739b9a9-38b1-4c79-ba4e-fde143ea680b](https://github.com/user-attachments/assets/5b48b54f-2d99-4c6b-b1b2-2a677b4a25fe)


- ## Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.

![435739514-051c53c4-0f8f-4846-88cd-d02469e9d656](https://github.com/user-attachments/assets/8dba6faa-268e-4d8c-a5c0-b0f22dc765bf)

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.

