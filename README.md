⚙️ 4-Bit Calculator (Transistor-Level Implementation)

💡 Overview

This project demonstrates the implementation of a 4-bit adder/subtractor built entirely from transistors and resistors to represent fundamental digital logic gates (AND, OR, NOT, XOR, NAND).
The design highlights how complex digital systems such as adders can be constructed at the transistor level, without relying on prebuilt logic gate components.


🧩 Design Description

The circuit implements four cascaded 1-bit full adders, each composed of 2 XOR gates, 2 AND gates, and 1 OR gate.
This forms a complete 4-bit arithmetic circuit capable of performing both addition and subtraction of two 4-bit binary numbers.


🔋 Design Highlights

Implemented all logic gates using BJTs and resistors

No pre-built logic blocks or behavioral modeling used

Switch-based input system for A, B, and Add/Subtract mode

LED indicators used for outputs 



🧠 Logic Gate-Level Schematic

This schematic shows the logic-level design of the 4-bit adder/subtractor before implementing it with discrete transistors.

![Logic Gate Schematic](images/Logic%20Gate%20Implementation.png)



⚡ Transistor-Level Schematic

Below is the transistor-level implementation of the full 4-bit adder/subtractor built using BJTs and resistors.

![Transistor Implementation Schematic](images/4%20Bit%20Adder%20Subtractor.png)

```markdown
📁 Folder Structure
📁 4-Bit-Calculator

├── circuits/ # Micro-Cap simulation circuit files (.cir)
│ ├── AND_gate.cir
│ ├── OR_gate.cir
│ ├── NOT_gate.cir
│ ├── NAND_gate.cir
│ ├── XOR_gate.cir
│ ├── Full_Adder.cir
│ └── 4 Bit Adder Subtractor.cir
│
├── images/ # Screenshots and schematic images
│ ├── AND_gate.png
│ ├── OR_gate.png
│ ├── NOT_gate.png
│ ├── NAND_gate.png
│ ├── XOR_gate.png
│ ├── Full_Adder.png
│ ├── 4_Bit_Adder_Subtractor.png
│ └── Logic Gate Implementation.png
│
├── simulations/ # Simulation of addition and subtraction tests
└── README.md # This file
```
📂 Files

AND_gate.cir, OR_gate.cir, NOT_gate.cir, XOR_gate.cir, NAND_gate.cir → transistor-level logic gate implementations

Full_Adder.cir → single-bit full adder schematic

4_Bit_Adder_Subtractor.cir → complete 4-bit adder/subtractor built from four full adders

images/ → contains screenshots of circuit schematics 

simulations/ → contains images of circuit simulations for addition and subtraction

🚀 Future Work

Improve transistor-level efficiency by reducing component count and optimizing biasing

Develop a transistor-based 4-bit multiplier using similar design principles
