# Weekly Update: CCSDS Protocol Project

This week's progress on the CCSDS Protocol Project includes the following developments:

## 1. Objective Review
The primary objective of the project is to understand and implement the CCSDS (Consultative Committee for Space Data Systems) protocol. The key focus areas are:
- Studying the CCSDS protocol stack and analyzing communication overheads.
- Identifying and evaluating open-source platforms that align with CCSDS implementation requirements.
- Establishing a testbed to simulate and test CCSDS protocol functionality.

## 2. Platform Exploration
We identified and evaluated several open-source platforms for potential CCSDS protocol implementation. Each platform was assessed based on the following criteria:
- GitHub activity and support.
- Programming language compatibility with project requirements.
- Ease of installation and setup.
- Regular maintenance and updates.
- Features supporting CCSDS communication standards.

### Shortlisted Platforms:
#### 1. **Cosmos (COSMOS Open Source Mission Operations System)**
- **GitHub Repository:** [COSMOS](https://github.com/BallAerospace/COSMOS)
- **Description:** Provides a complete suite of tools for telemetry and command in space systems.
- **Features:**
  - Integrated tools for data parsing and visualization.
  - Extensive documentation and active community support.
- **Language:** Ruby.
- **Maintenance:** Actively maintained.
- **Hardware Requirements:** Software-only, no specialized hardware required.

#### 2. **OpenSatKit**
- **GitHub Repository:** [OpenSatKit](https://github.com/OpenSatKit/OpenSatKit)
- **Description:** A development and operations environment for satellite systems.
- **Features:**
  - CCSDS protocol support for telemetry and commanding.
  - Compatibility with hardware and simulation tools.
- **Language:** C and Python.
- **Maintenance:** Actively maintained.
- **Hardware Requirements:** Software-based testbeds supported.

#### 3. **CLTU Simulator**
- **GitHub Repository:** [CLTU Simulator](https://github.com/NASA-GSFC/CLTU-Simulator)
- **Description:** Command Link Transmission Unit Simulator for CCSDS uplink protocols.
- **Features:**
  - High-fidelity simulation of CCSDS uplink protocols.
  - Lightweight, easy deployment.
- **Language:** Python.
- **Maintenance:** NASA-supported, actively maintained.
- **Hardware Requirements:** None.

#### 4. **GSWS (Generic Spacecraft Workbench Simulator)**
- **GitHub Repository:** [GSWS](https://github.com/esa/GSWS)
- **Description:** A modular spacecraft simulation framework.
- **Features:**
  - Protocol simulation with CCSDS-compliant interfaces.
  - Modular architecture for flexible usage.
- **Language:** Java.
- **Maintenance:** Actively maintained by ESA.
- **Hardware Requirements:** None.

## 3. Research Materials
The following CCSDS documents were consulted to guide the platform evaluation and protocol analysis:
- **CCSDS 131.0-B-3**: TM Synchronization and Channel Coding. [Available here](https://public.ccsds.org/Pubs/131x0b3.pdf)
- **CCSDS 232.0-B-1**: Telecommand Part 1 - Communications Protocol. [Available here](https://public.ccsds.org/Pubs/232x0b1.pdf)
- **CCSDS 734.1-B-1**: Proximity-1 Space Link Protocol - Data Link Layer. [Available here](https://public.ccsds.org/Pubs/734x1b1.pdf)

## 4. Next Steps
- Finalize the platform selection based on the project's technical requirements and platform features.
- Begin setting up the testbed using the chosen platform.
- Document findings and prepare initial protocol simulation experiments.

## 5. Challenges
- Ensuring platform compatibility with the specific requirements of CCSDS protocols.
- Identifying solutions for interplanetary communication challenges, especially for Mars-Earth scenarios.

## 6. Upcoming Tasks
- Deepen understanding of CCSDS protocols through further study of Blue Books.
- Perform hands-on testing with the shortlisted platforms to determine feasibility.
- Develop a preliminary demonstration to showcase early results.

---

### Feedback Requested:
- Additional criteria for platform evaluation.
- Recommendations for alternative tools or repositories.
- Advice for addressing interplanetary communication challenges in CCSDS implementation.
