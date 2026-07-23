# 5G_Projects
This repository contains a 5G Network Simulation project that demonstrates the architecture, communication, and performance analysis of fifth-generation (5G) wireless networks.

Software Requirements:
- Ubuntu 22.04
- Open5GS
- MongoDB
- Node.js 20
- Open5GS WebUI
- Python 3
- Matplotlib
- iperf3

ASSIGNMENT 1:

This project demonstrates a software-based 5G network simulation using Open5GS. The experiment measures TCP uplink and downlink throughput for a single traffic flow over 60 seconds using iperf3. The collected performance data is stored in JSON format and visualized using Python and Matplotlib.
The project helps understand the behaviour of TCP traffic in a virtualized 5G Core Network and compares uplink and downlink throughput.

Features:
- Open5GS based 5G Core Network
- TCP Uplink Traffic Generation
- TCP Downlink Traffic Generation
- Single Flow Performance Analysis
- Throughput Visualization
- Uplink vs Downlink Comparison
- JSON Output Processing
- Python Graph Generation

Inference:

The project successfully demonstrates TCP uplink and downlink traffic analysis using the Open5GS 5G Core Network. By generating TCP traffic with iperf3 and visualizing the results using Python and Matplotlib, the project evaluates network throughput under a single-flow scenario. The analysis shows that downlink throughput is slightly higher and more stable than uplink throughput, while uplink traffic exhibits greater fluctuations due to TCP congestion control. Overall, the project validates the effectiveness of Open5GS as a software-based platform for 5G network performance evaluation and provides a foundation for future research on QoS, latency, multi-user traffic, and advanced 5G network simulations.

ASSIGNMENT 2:

To capture and analyze live traffic from a running Open5GS 5G core network, produce a verified Interface/Protocol map identifying all key 5G interfaces and their transport protocols, and specifically identify and confirm the transport protocol used for the N2 interface using Wireshark packet capture analysis. 

Features:
- Live packet capture and analysis using Wireshark.
- Verification of 5G Core Network interface protocols.
- Identification of the N2 interface transport protocol (SCTP).
- Analysis of NGAP signaling between AMF and gNB.
- Verification of N3 (UDP/GTP-U), N4 (UDP/PFCP), and SBI (TCP/HTTP2) interfaces.
- Open5GS-based software 5G Core Network implementation.
- Packet filtering and protocol inspection using Wireshark.
- TUN (ogstun) interface configuration for network communication.
- Protocol mapping of key 5G interfaces from live traffic.
- Suitable for learning, testing, and validating 5G network architecture.

Inference:

This project analyzes live Open5GS 5G Core Network traffic using Wireshark to verify key 5G interface protocols. It confirms that the **N2 interface** uses **SCTP/NGAP**, while the **N3**, **N4**, and **SBI** interfaces use **UDP/GTP-U**, **UDP/PFCP**, and **TCP/HTTP2**, respectively. The project demonstrates the protocol architecture of a software-based 5G core network and validates it through live packet analysis.
