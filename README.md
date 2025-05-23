# MonkeyWrenchAI

**AI diagnostic companion and cybersecurity anomaly detection on CAN bus communication level**

---

## Overview

**MonkeyWrenchAI** is an open-source, AI-powered diagnostic tool designed to detect, classify, and analyze cybersecurity-related anomalies on automotive CAN (Controller Area Network) bus systems. It empowers automotive engineers, R&D departments, security researchers, and hobbyists to simulate attacks, diagnose real-world CAN logs, and access advanced bidirectional scan tool capabilities—all through a modern, modular, and extensible platform. I will be reaching out to manufacturers on getting access to database for training AI.

---

## Manufacturer Datasets

To ensure robust AI and ML performance, MonkeyWrenchAI supports structured datasets for various vehicle manufacturers. You can contribute datasets for different brands or use the provided templates to begin gathering your own.

### How to Contribute a Dataset

1. Copy the appropriate template from the `data-templates/` directory (see below).
2. Fill in the dataset with real, anonymized, and properly licensed CAN bus logs or diagnostic data.
3. Document the source and any restrictions in the header of your dataset file.
4. Submit a pull request or contact [your-email@example.com] for inclusion.

### Supported Brands (Templates Provided)

- Ford
- Toyota
- [Add more as needed]

See `data-templates/` for starter files.

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
Coming Soon(hopefully)

