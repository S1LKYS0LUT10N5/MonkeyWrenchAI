# MonkeyWrenchAI

**AI diagnostic companion and cybersecurity anomaly detection on CAN bus communication level**

---

## Overview

**MonkeyWrenchAI** is an open-source, AI-powered diagnostic tool designed to detect, classify, and analyze cybersecurity-related anomalies on automotive CAN (Controller Area Network) bus systems. It empowers automotive engineers, R&D departments, security researchers, and hobbyists to simulate attacks, diagnose real-world CAN logs, and access advanced bidirectional scan tool capabilities—all through a modern, modular, and extensible platform.

---

## Features

- **AI-Powered Anomaly Detection:**  
  Utilizes both machine learning and deep learning to detect, classify, and provide root cause analysis for anomalies across fCAN and bCAN modules (e.g., Body Control Module, Security Module, ECM, TCM, etc.).

- **Attack Simulation & Real Log Analysis:**  
  Supports both simulated CAN bus attacks and the analysis of real CAN logs for comprehensive security and diagnostic workflows.

- **Bidirectional Diagnostics:**  
  Enables diagnostic commands, calibration, and repair procedures, integrating manufacturer-specific repair data and TSBs (with licensing/compliance).

- **All Major Automotive Data Formats:**  
  Compatible with .asc, .blf, .csv, .dbc, OBD-II PIDs, UDS, ISO-TP, and more.

- **Modular & Extensible:**  
  Easily add custom modules for detection, simulation, or manufacturer-specific ECUs. Future-ready for PCM tuning and aftermarket ECU support.

- **Modern UI:**  
  Scan tool-style interface with live data graphs, event logs, bidirectional controls, and Bluetooth vehicle communication.

- **Research & Community Driven:**  
  Designed for automotive researchers, hobbyists, and manufacturers. Contributions are welcomed—bring your detection modules, datasets, attack simulations, and security patches!

---

## Getting Started

### Prerequisites

- Python 3.8+ (or specify language/toolchain as appropriate)
- [Add additional dependencies here]
- Bluetooth-enabled CAN interface (for live vehicle connectivity)

### Installation

```bash
git clone https://github.com/S1LKYS0LUT10N5/MonkeyWrenchAI.git
cd MonkeyWrenchAI
# Install dependencies
pip install -r requirements.txt
