# Project 3: Wireshark Network Traffic Analysis

## Objective
Analyze captured network traffic using Wireshark to understand network communication, identify protocols, and investigate selected TCP and DNS activity.

## Tools Used
- Wireshark
- Windows

## Analysis Performed

### 1. DNS Analysis
- Identified DNS queries and responses.
- Observed a DNS query for `chatgpt.com`.
- Examined the returned IPv4 addresses.

### 2. TCP Three-Way Handshake
- Identified SYN, SYN-ACK, and ACK packets.
- Examined the connection between the local system and a remote HTTPS endpoint.

### 3. TLS Analysis
- Inspected TLS Client Hello and Server Hello messages.
- Observed TLS 1.3 negotiation and the selected cipher suite.

### 4. Protocol Analysis
- Reviewed the Protocol Hierarchy.
- Examined IPv4, IPv6, TCP, UDP, DNS, and mDNS traffic.

### 5. TCP Investigation
- Applied TCP reset and retransmission display filters.
- Observed TCP RST packets.
- No packets matched the retransmission filter in this capture.

### 6. Traffic Statistics
- Reviewed IPv4, TCP, and UDP conversations.
- Examined network endpoints and traffic distribution.
- Used the I/O Graph to observe packet activity over time.

## Key Learning Outcomes
- Understanding DNS request and response patterns.
- Recognizing TCP connection establishment.
- Understanding TLS handshake information.
- Using Wireshark display filters.
- Reviewing network conversations, endpoints, and protocol statistics.

## Conclusion
This project provided practical experience in packet analysis and network traffic investigation using Wireshark. It strengthened my understanding of common network protocols and helped develop foundational skills relevant to Security Operations Centre (SOC) analysis.
