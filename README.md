# PCAP 1

## Objective

I’ll be putting my Wireshark skills to the test

### Skills Learned

- **Packet Capture Analysis:** Learn how to capture and examine network traffic to identify unusual patterns like port scanning.
- **Protocol Dissection:** Gain experience in dissecting various network protocols (e.g., TCP, UDP, ICMP) to analyze specific packet details.
- **Traffic Filtering:** Practice filtering specific IP addresses, ports, and protocols to focus on the relevant traffic for analysis.
- **Anomaly Detection:** Learn how to spot anomalies in traffic patterns, such as unusual frequency or volume of requests.
- **Flow Analysis:** Study communication flows between internal systems to detect unauthorized or suspicious interactions.
- **Evidence Collection:** Collect and interpret network data to support incident investigation and reporting.

### Tools Used

- Wireshark for capturing and examining network traffic to investigate the 'Local to Local Port Scanning' alert.
- Packet Capture File (PCAP) provided for detailed analysis of network communication between internal systems.
- VirtualBox used as the virtual machine platform to simulate the environment for traffic analysis, ensuring a controlled and isolated space for investigation.

## Steps
### 1. Which protocol was used over port 3942?
Go to Statistics > Endpoints > UDP > Right click on the line with port 3942 > apply as filter > selected. Then return to the main screen of wireshark and check the protocol.
<div><img width="373" alt="image" src="https://github.com/user-attachments/assets/251e8f7e-7a77-4df8-b94e-29e702c7227c" /></div>
Answer: SSDP

