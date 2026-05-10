# Wireshark-
Catching the packets
# Wireshark Packet Analysis: HTTP, DNS, and TLS

## Project Description
This project demonstrates practical network traffic analysis using Wireshark on Kali Linux. By capturing and inspecting packets, I have analyzed the structure and flow of HTTP, DNS, and TLS protocols.

## Objectives
- Analyze unencrypted HTTP traffic.
- Observe DNS resolution queries and responses.
- Inspect the TLS handshake process for secure communication.

## Analysis Summary
- **HTTP:** Filtered for `GET` requests to observe plaintext headers.
- **DNS:** Identified query/response pairs on UDP Port 53.
- **TLS:** Analyzed the `Client Hello` and `Server Hello` handshake packets.

## Tools Used
- **OS:** Kali Linux
- **Tool:** Wireshark
- **Environment:** Live Network Capture

## Files in this Repository
- `/screenshots`: Visual evidence of analyzed packets.
- `/captures`: The raw .pcapng capture file.
- `Wireshark_Packet_Analysis_Report.pdf`: Detailed project report.
