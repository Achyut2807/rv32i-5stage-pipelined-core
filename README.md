# 5-Stage Pipelined RV32I Core — RTL to GDS-II (100 MHz)

[![Architecture](https://img.shields.io/badge/ISA-RISC--V%20RV32I-blue.svg)](#)
[![PDK](https://img.shields.io/badge/PDK-SAED%2032nm-green.svg)](#)
[![Clock](https://img.shields.io/badge/Clock-100%20MHz%20(10.0ns)-blue.svg)](#)
[![Timing](https://img.shields.io/badge/WNS%20%2F%20TNS-0.00%20ns-brightgreen.svg)](#)
[![EDA](https://img.shields.io/badge/EDA-VCS%20%7C%20Verdi%20%7C%20DC%20%7C%20ICC2%20%7C%20PT-orange.svg)](#)

Design, simulation-based verification, and physical implementation of a **5-stage pipelined RV32I RISC-V processor** (IF, ID, EX, MEM, WB) featuring hazard detection, data forwarding, and branch flush logic on the **SAED32nm** PDK.

---

## 📊 Physical Design & Timing QoR Signoff

| Parameter | Metric / Value | Signoff Status |
|---|---|---|
| **Clock Period** | **10.0 ns** | Met |
| **Clock Frequency** | **100 MHz** | Clean |
| **Setup Slack (WNS)** | **+0.02 ns** (MET) | Zero Violations |
| **Hold Slack** | **+0.64 ns** (MET) | Zero Violations |
| **Total Negative Slack (TNS)** | **0.00 ns** | 0 Violating Paths |
| **Operating Condition** | `ss0p7vn40c` | Signoff Corner |

---

## 👤 Author
**Achyut Bhanderi** — [GitHub](https://github.com/Achyut2807) | [LinkedIn](https://linkedin.com/in/achyut-bhanderi)
