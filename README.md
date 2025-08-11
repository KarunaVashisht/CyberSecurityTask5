# CyberSecurityTask5
Task 5  : Capture and Analyze Network Traffic Using Wireshark


<h4>OVERVIEW:</h4>
This project demonstrates the capture and analysis of live network traffic using Wireshark.
The goal was to generate network activity, capture packets over Wi-Fi, and identify multiple network protocols by analyzing their packet details.

<h4>PROCEDURE FOLLOWED:</h4>
- Installed and launched Wireshark.<br>
- Selected the active Wi-Fi interface for capture.<br>
- Traffic Generation starts.<br>
- Performed ping requests to a known domain to generate ICMP and DNS traffic.<br>
- Browsed a website (Flipkart) to generate TCP, HTTP, and TLS/HTTPS traffic.<br>
- Captured traffic for approximately one minute.<br>
- Stopped the capture and applied filters (icmp, dns, tcp, http, tls) to isolate protocols.

<h4>IDENTIFIED PROTOCOLS:</h4>
- DNS – Domain name resolution for website access.<br>
- TCP – Connection-oriented transport protocol.<br>
- HTTP – Unencrypted web requests.<br>
- TLS/HTTPS – Secure encrypted web communication.

<h4>PROJECT FILES:</h4>
- wireshark_capture.pcapng – Raw packet capture file from Wireshark containing the recorded network traffic.<br>
- Wireshark Network Traffic Analysis Report.pdf – Detailed analysis of captured packets, including identified protocols, packet counts, purposes, and example packet details.
