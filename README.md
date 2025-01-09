# Reliable Data Transfer Protocol Simulator

## Overview
This project simulates a **Reliable Data Transfer Protocol** using the **Go-Back-N (GBN)** algorithm. It models the interaction between two entities (Sender and Receiver) over a simulated network with configurable parameters such as packet loss, corruption, and arrival rate. The simulator includes multiple test cases to evaluate the performance of the protocol under varying conditions.

---

## Features
### Go-Back-N Protocol Implementation:
- Handles data transfer, acknowledgments, and retransmissions.
- Ensures reliable delivery of packets despite packet loss and corruption.

### Network Simulation:
- Configurable parameters for packet loss, corruption probability, and timer intervals.
- Simulates the effects of network conditions like packet loss and corruption.

### Comprehensive Testing:
- Includes pre-defined test cases to evaluate protocol performance.
- Provides detailed logs and reports for debugging and analysis.

---

## Project Structure
- **`network_simulator.py`**:
  - Implements the simulated network layer and event management.
  - Handles packet loss, corruption, and transmission delays.
  
- **`gbn_host.py`**:
  - Implements the Go-Back-N protocol logic for sending and receiving data.
  - Manages sliding window, retransmissions, and acknowledgment handling.
  
- **`rdt_tester.py`**:
  - Manages test execution and validation.
  - Includes test configurations and result comparisons.
