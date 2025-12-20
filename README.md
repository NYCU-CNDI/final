# final

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
