# Batbot 🦇🤖

**Training a bat-inspired flapping wing robot to hover using evolutionary algorithms.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.12](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/)
[![DOI](https://img.shields.io/badge/DOI-10.1007/978--981--96--1464--6__27-blue.svg)](https://doi.org/10.1007/978-981-96-1464-6_27)

---

## Overview

Batbot is a **bat-inspired flapping wing robot** with synchronized wing morphing. This project developed an **evolutionary algorithm-based control strategy** to optimize flight parameters — shifting from manual tuning to data-driven optimization.

**Key achievements:**
- Novel mechanism synchronizing wing flapping with wing morphing
- Evolutionary algorithm optimizing flight control from scratch
- Published as a Springer book chapter (IFToMM CCMMS 2024)

---

## Publications

Santoyo Alum, A.; Li, J.; Harouna, G.; Wang, Z.; Zhao, J. "Design of a Bat-inspired Flapping Robot." In: *Advances in Mechanism and Machine Science and Engineering in China — IFToMM CCMMS 2024*. Springer, 2024.
[DOI: 10.1007/978-981-96-1464-6_27](https://doi.org/10.1007/978-981-96-1464-6_27)

---

## Project Structure

```
├── MicroPython/          # On-board robot firmware
├── analysis/             # Data analysis notebooks
├── experiments/          # Experimental data and logs
├── archive/              # Previous versions and prototypes
├── anna_pi.ipynb         # Main analysis notebook
├── optimizer_batbot.py   # Evolutionary algorithm optimizer
├── optimizer_batbot_mimic.py  # Mimic-based optimizer
├── grid_test_batbot.py   # Grid search testing
└── utils.py              # Utility functions
```

---

## How It Works

1. **Robot design:** 3D-printed bat-inspired frame with silicone membrane wings
2. **Control optimization:** CMA-ES evolutionary algorithm tunes wingbeat parameters
3. **On-board deployment:** MicroPython firmware runs the optimized controller
4. **Analysis:** Sensor data analyzed to validate flight performance

---

## Quick Start

```bash
# Install dependencies
pip install numpy scipy matplotlib

# Run the optimizer
python optimizer_batbot.py

# Or test with grid search
python grid_test_batbot.py
```

---

## Acknowledgments

**Master's thesis, Tsinghua University (2022–2024)**
Supervisor: Prof. Jingshan Zhao · Robotics & Mechanism Lab
Awarded **Excellence Scholarship** by the Chinese government.

---

## License

MIT
