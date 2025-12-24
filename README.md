# 1-Bit Full Adder – Analog & VLSI Design 🛠️⚡

A transistor-level CMOS design project for implementing a 1-bit full adder using basic logic gates and modular design principles.

## Table of Contents

* [Project Overview](#project-overview)
* [Features](#features)
* [Installation / Tools](#installation--tools)
* [Implementation](#implementation)
* [Results](#results)
* [Future Work](#future-work)
* [License](#license)

## Project Overview

This project focuses on designing a 1-bit full adder at the transistor level using CMOS logic. The design was hierarchical—starting from constructing basic NAND, NOR, and inverter gates, building half adders, and finally combining them to form a full adder.

A full adder computes the sum of three input bits (A, B, Cin) and outputs the Sum and Carry, forming a fundamental building block for digital circuits.

## Features

* **Hierarchical Design:** Built a full adder using two half adders and an OR gate for carry propagation.
* **Transistor-Level Gates:** NAND, NOR, and Inverter gates implemented using static CMOS (PMOS + NMOS).
* **Optimization:** Proper transistor sizing to optimize propagation delay and power efficiency.
* **Modular Design:** Half adder symbols reused to construct full adder symbol, demonstrating modularity.

## Installation / Tools

* **Software:**  LTSpice and Simulink.
* **Environment:** CMOS technology library for PMOS and NMOS transistors.

## Implementation

1. **Gate Construction:**

   * Designed NAND, NOR, and Inverter gates at transistor level using CMOS logic.
2. **Half Adder Design:**

   * Built a half adder using the basic gates.
3. **Full Adder Design:**

   * Combined two half adders and an OR gate to create a 1-bit full adder symbol.
4. **Simulation & Verification:**

   * Verified correctness of Sum and Carry outputs under all input combinations.

## Results

* Successfully designed a fully functional transistor-level 1-bit full adder.
* Demonstrated correct Sum and Carry outputs for all input combinations.
* Achieved optimized propagation delay and low power consumption at the transistor level.
* Reinforced understanding of CMOS logic, gate-level design, and VLSI fundamentals.

## Future Work

* Extend design to multi-bit adders (4-bit, 8-bit) using ripple-carry or carry-lookahead architectures.
* Explore low-power and high-speed transistor-level optimizations.
* Implement on FPGA or ASIC for practical testing.

## Citation

If you use this work, please cite:

```bibtex
@software{1-Bit-Full-adder-in-LTspice,
  author = {Shubhan Mital},
  title = {1 Bit Full adder in LTspice},
  year = {2025},
  url = https://github.com/Shubhanflash22/1-Bit-Full-adder-in-LTspice.git
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
