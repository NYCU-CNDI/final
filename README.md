# final

## Group 1: [Efficient and Hardware-Independent Deep Packet Inspection for Free5GC](https://github.com/c1ydehhx/dpi5g)

Since Ian Chen mentioned that Free5GC UPF doesn't have Deep Packet Inspection (DPI) feature in CNDI course, it caught my interest to implement a DPI feature. After doing some research, most DPI feature is handle with hardware support such as P4 programmable switch. We just happend to have a P4 switch in our Lab, so it's a perfect timing to start this research project. Construct hardware-support DPI solution is easy and straight forward. It's easy for me to construct this since I have some experience on P4 Switch. To make it more challenge, We trying to find a Hardware-Independent solution that can achieve efficient as same as hardware-support solution (Like, P4 Switch). It's interesting that discovery a hardware-independent solution and it increase the possibility that we can integrate into Free5GC UPF.

For the information about our PoC, please refer [this blog](https://www.c1ydeh.net/#/blog/2025f-free5gc-dpi).

## Group 2: [Parallelizing the NGAP Message Processing Architecture in free5GC AMF](https://github.com/qawl987/amf)

This project implements a high-performance parallel NGAP message processing architecture in the free5GC AMF, replacing the sequential SCTP handling model to resolve Head-of-Line blocking. It utilizes a lock-free dispatching mechanism with a UE-ID based hashing scheduler to distribute signaling loads across worker pools. This design guarantees per-UE message ordering while maximizing multi-core utilization, resulting in a 3.66x speedup in registration time and significantly higher success rates under simulated signaling storms.

## Group 3: [free5GC-MCP (Model Context Protocol) Server](https://github.com/q1317540161/free5gc-MCP)

This project is an MCP (Model Context Protocol) server implemented in Go that provides AI assistants (like GitHub Copilot) with tools to manage free5GC 5G core network subscribers and configurations.

### Features

- **Core Network Control**: Start, stop, and monitor all free5GC network functions (NRF, AMF, SMF, UPF, etc.)
- **Subscriber Management**: Full CRUD operations for 5G subscribers
- **Tenant User Management**: Query users within tenants
- **JWT Authentication**: Automatic authentication with free5GC webconsole
- **VS Code Integration**: Works seamlessly with GitHub Copilot in VS Code

## Group 4: [free5GC-trace](https://github.com/ChenYen-Yen/free5gc-trace)

This project implements end-to-end distributed tracing for the UE Registration procedure in a free5GC-based 5G Core, using OpenTelemetry and Grafana Tempo. It correlates SBI calls across six key NFs (AMF, AUSF, UDM, UDR, NSSF, NRF) into a single trace so that each UE registration can be visualized and debugged as one coherent flow.

## Group 5: [UPF Acceleration App using DOCA](https://github.com/stanleyshen2003/upf_accel)

This project implements an accelerated User Plane Function (UPF) datapath using NVIDIA DOCA on a DPU platform (BlueField). The goal is to offload packet processing, GTP encapsulation/decapsulation, and routing functions into hardware to greatly improve throughput while reducing CPU load.

This repository demonstrates how DOCA can accelerate a UPF in a complete test environment, using free5GC as the 5G Core control plane, UERANSIM to simulate UE and gNB traffic, and a DOCA Flow–based UPF application running on the DPU.

## Group 6: [Automation of free5GC ci-test](https://github.com/CNDI-final/web_test)

## Group 7: [5G-DPOP: 5G UPF Data Plane Observability Platform](https://github.com/solar224/5G-DPOP)

A 5G UPF observability platform powered by eBPF. Features real-time traffic monitoring, granular packet drop detection, and PFCP session correlation for free5GC without source code modification.

## Group 8: [RESTful API Fuzzing for Free5GC](https://github.com/freddy645645/5GC-Fuzz)

## Group 9: [Fast PDU Session Cleanup](https://github.com/c9274326/CNDI_Group9.git)
