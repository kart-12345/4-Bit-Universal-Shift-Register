# 4-Bit-Universal-Shift-Register
Implementation of 4 bit universal shift register in 45nm technology node in cadence.
# Full Custom Design and Layout of a 4-Bit Universal Shift Register Using CMOS Technology
## Project Overview
This project focuses on the full-custom transistor-level design and layout implementation of a **4-Bit Universal Shift Register** using CMOS technology in Cadence Virtuoso.
The design consists of four Master-Slave D Flip-Flops and four 4:1 Multiplexers, providing four operating modes: Hold, Shift Left, Shift Right, and Parallel Load.
Instead of using predefined standard cells, each building block is designed from the transistor level to achieve a complete full-custom implementation.
## Design Architecture
The design is implemented using the following hierarchical approach:

- **Master-Slave D Flip-Flop:** Designed using NAND gates and NOT gates to achieve edge-triggered data storage.
- **2:1 Multiplexer:** Implemented using CMOS transmission gates for efficient data selection.
- **4:1 Multiplexer:** Constructed using three 2:1 multiplexers arranged in a hierarchical structure.
- **4-Bit Universal Shift Register:** Implemented by integrating four Master-Slave D Flip-Flops and four 4:1 Multiplexers.
## Operating Modes
The universal shift register supports four different operations:

1. **Hold:** Retains the previously stored data.
2. **Shift Right:** Shifts the stored data by one position towards the right.
3. **Shift Left:** Shifts the stored data by one position towards the left.
4. **Parallel Load:** Loads four input bits simultaneously into the register.

## Implementation Flow

The project follows a complete full-custom VLSI design flow:

1. Transistor-level schematic design of NAND and NOT gates.
2. Design and simulation of Master-Slave D Flip-Flops.
3. Implementation of 2:1 multiplexers using transmission gates.
4. Construction of 4:1 multiplexers using 2:1 multiplexers.
5. Integration of the complete 4-bit Universal Shift Register.
6. Functional verification through transient simulations.
7. Layout design and implementation.
8. Design Rule Check (DRC) and Layout Versus Schematic (LVS) verification.

## Tools and Technology

- **EDA Tool:** Cadence Virtuoso
- **Design Approach:** Full-Custom Transistor-Level Design
- **Technology:** 45nm CMOS
- **Circuit Design:** CMOS Logic and Transmission Gates
- **Verification:** Transient Analysis, DRC and LVS
- **Implementation:** Schematic to Layout

## Key Learning Outcomes

- Understanding transistor-level CMOS circuit design.
- Designing Master-Slave D Flip-Flops using NAND and NOT gates.
- Understanding transmission-gate-based multiplexers.
- Developing hierarchical digital circuits.
- Understanding the working and operation of universal shift registers.
- Gaining practical experience in full-custom VLSI design and physical layout implementation.

**Project Outcome:** A complete transistor-level 4-bit Universal Shift Register designed and implemented from individual logic gates to the final physical layout using Cadence Virtuoso.
