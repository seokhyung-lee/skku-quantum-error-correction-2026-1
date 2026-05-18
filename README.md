# Lab Materials for 2026-1 Quantum Error Correction (EQE5006), Sungkyunkwan University

Lecturer: Prof. [Seok-Hyung Lee](https://seokhyung-lee.github.io)

## Overview

Lab materials (Jupyter notebooks) for the graduate course **EQE5006 Quantum Error Correction** at Sungkyunkwan University (SKKU) in Spring 2026. The labs use [stim](https://github.com/quantumlib/Stim), a high-performance stabilizer circuit simulator.

## Labs

| # | Date | Topic | Notebook |
|---|------|-------|----------|
| 1 | 2026/03/17 | Stim basics and quantum circuit simulation | [lab1-stim-basics.ipynb](labs/lab1-stim-basics.ipynb) |
| 2 | 2026/03/24 | Pauli group and Clifford group in stim | [lab2-pauli-clifford-in-stim.ipynb](labs/lab2-pauli-clifford-in-stim.ipynb) |
| 3 | 2026/03/31 | Introduction to quantum error correction in stim | [lab3-intro-to-qec.ipynb](labs/lab3-intro-to-qec.ipynb) |
| 7 | 2026/05/07 | QEC circuit simulation in stim | [lab7-qec-circuit-simulation.ipynb](labs/lab7-qec-circuit-simulation.ipynb) |
| 8 | 2026/05/19 | Circuit-level noise and repetitive syndrome extraction | [lab8-circuit-level-noise.ipynb](labs/lab8-circuit-level-noise.ipynb) |

## Requirements

- Python 3.10+
- `stim`, `numpy`, `matplotlib`, `pymatching`

```bash
pip install stim numpy matplotlib pymatching
```

## License

[MIT](LICENSE)
