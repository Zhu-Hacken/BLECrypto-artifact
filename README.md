# BLECrypto

BLECrypto is a static analysis framework for detecting cryptographic API misuses in Bluetooth Low Energy (BLE) communication in Android companion applications.

This repository serves as the artifact repository for the paper:

**"BLECrypto: Automatic Detection of Cryptographic API Misuses in BLE Communication"**

---

## 🔧 Status

🚧 The project is currently under preparation.

The full implementation and usage instructions will be released after final code cleaning and documentation.

---

## 📌 Overview

BLECrypto performs a two-stage static analysis:

1. **Stage 1**: Identify whether BLE communication data is protected by application-layer cryptographic operations.
2. **Stage 2**: Analyze the correctness of cryptographic configurations (e.g., algorithm, mode, key, IV) and detect potential misuses.

The framework is designed for large-scale analysis of Android applications interacting with BLE devices.

---

## 📊 Planned Release Contents

- Source code of BLECrypto
- Analysis pipeline implementation
- Usage instructions and documentation

---

## 📦 Dataset Availability

Due to licensing and distribution restrictions of Android applications, the dataset used in this study cannot be publicly released.

However, the dataset can be reconstructed from publicly available sources such as AndroZoo. Detailed instructions for data collection and preprocessing will be provided.

---

## 📄 License

This project is licensed under the MIT License.
