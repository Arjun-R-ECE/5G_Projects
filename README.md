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
