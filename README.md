![Language](https://img.shields.io/badge/Language-C%2B%2B-blue)
![HDL](https://img.shields.io/badge/Language-HDL-orange)
![JACK](https://img.shields.io/badge/Language-JACK-yellow)
![Progress](https://img.shields.io/badge/Progress-8%25-green)
# Building a Modern Computer from First Principles
### My Nand2Tetris Journey

## Overview
This repository contains my progress through the **Nand2Tetris** (The Elements of Computing Systems) course. The goal is to build a complete computer system (hardware and software) starting from nothing but a NAND gate.

## The Stack
- **Hardware:** HDL
- **Assembler:** C++
- **Virtual Machine:** C++
- **Compiler:** C++
- **OS:** Jack

## Project Roadmap
- [ ] **Part I: Hardware**
    - [X] Project 1: Boolean Logic
    - [ ] Project 2: Boolean Arithmetic
    - [ ] Project 3: Sequential Logic
    - [ ] Project 4: Machine Language
    - [ ] Project 5: Computer Architecture
- [ ] **Part II: Software**
    - [ ] Project 6: Assembler
    - [ ] Project 7-8: Virtual Machine
    - [ ] Project 9: High-Level Language (Jack)
    - [ ] Project 10-11: Compiler
    - [ ] Project 12: Operating System

## Personal Reflections
### Project 1
- I started with standard "Sum of Products" logic but used Boolean identities and De Morgan's Laws to drastically reduce gate counts.
- For chips like Or8Way, I implemented a Binary Tree instead of a serial cascade to minimize propagation delay from $O(n)$ to $O(\log n)$.
- Learned to handle 16-bit buses and sub-busing (e.g., sel[0..1]) to create modular, readable hardware designs.

---

*Note: This repository is for educational purposes. If you are currently taking the course, I highly encourage you to solve the puzzles yourself before looking at my implementation!*