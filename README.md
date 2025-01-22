# Ccsds-Protocol-Testbed

## Overview
This repository is dedicated to implementing and testing the CCSDS (Consultative Committee for Space Data Systems) protocol stack on an open-source platform. The primary goal is to create a functional testbed that allows the analysis of communication mechanisms, protocol stack behavior, and associated overheads, particularly in interplanetary communication scenarios.

---

## Objectives
- **Study and Implementation:** Develop a detailed understanding of the CCSDS protocol stack and implement its layers using an open-source platform.
- **Evaluation:** Analyze communication mechanisms, protocol efficiency, and overheads in a simulated environment.
- **Adaptability:** Ensure the testbed aligns with CCSDS standards while allowing modifications to evaluate different scenarios.

---

## Selected Open-Source Platform
### Repository: [OpenSatKit](https://github.com/OpenSatKit/OpenSatKit)
- **Purpose:** Satellite command and control system with CCSDS protocol support.
- **Programming Language:** C, Lua.
- **Key Features:**
  - Detailed CCSDS protocol implementation.
  - Active community and consistent updates.
  - Comprehensive documentation.
  - Compatible with software-only environments.
- **Rationale for Selection:** OpenSatKit is robust, feature-rich, and has a strong focus on CCSDS compliance. It provides a good foundation for implementing and testing communication protocols.

---

## Repository Structure
```plaintext
ccsds_protocol_testbed/
├── docs/                     # Documentation for CCSDS protocols and setup
├── src/                      # Source code for protocol implementation
│   ├── layer1/               # Physical layer implementation
│   ├── layer2/               # Data link layer
│   ├── layer3/               # Network layer
│   └── utils/                # Utility scripts and tools
├── test/                     # Test cases for protocol validation
├── tools/                    # Tools for simulation and data visualization
├── README.md                 # Repository overview and setup instructions
└── LICENSE                   # License details
```

---

## Setup Instructions
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/ccsds_protocol_testbed.git
   cd ccsds_protocol_testbed
   ```

2. **Install Dependencies:**
   Ensure the necessary compilers, libraries, and dependencies for C and Lua are installed.
   ```bash
   sudo apt-get update
   sudo apt-get install gcc make lua5.3
   ```

3. **Build the Testbed:**
   Run the build script to compile the source code.
   ```bash
   make all
   ```

4. **Run Simulations:**
   Use provided scripts to initiate test cases and observe protocol behavior.
   ```bash
   ./run_tests.sh
   ```

---

## Roadmap
- [x] Select an open-source platform.
- [x] Define repository structure and objectives.
- [ ] Implement physical and data link layers.
- [ ] Test and validate CCSDS protocol behavior.
- [ ] Add support for higher layers and end-to-end simulation.
- [ ] Document findings and publish results.

---

## References
- CCSDS Standards Documentation: [https://public.ccsds.org](https://public.ccsds.org)
- OpenSatKit GitHub Repository: [https://github.com/OpenSatKit/OpenSatKit](https://github.com/OpenSatKit/OpenSatKit)
