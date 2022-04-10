---
title: "8-Bit CPU VHDL Implementation."
permalink: /cpu/
author_profile: false
toc: true
# toc_label : "AES Table of Contents"
toc_icon: "book"
sidebar:
  - title: "Projects"
    nav: sidebar-sample
---

- Give a brief overview here of the project

# Main Parts of a CPU

- talk about CPU architecture
- have a block diagram explaining it

## Control Unit (CU):

The Control Unit fetches and decodes the incoming instructions, in order to control how the other components operate. It is primarily used to transfer data and instructions around the system.

## Arithmetic Logic Unit (ALU):

The ALU consists of logic gates and is used to perform arithmetic and logical operations (decisions). Any data that is transfered between the primary and secondary storage is also passed through the ALU.

## Registers:

Registers are used in a CPU to store small amounts of data during processing. There are five types of registers within a CPU, found below:

### Accumulator - AC
Stores the results of caluclations.

### Instruction Register - IR
Stores the address in RAM of the instruction to be processed.

### Memory Address Register - MAR
Stores the address in RAM of the data to be processed.

### Memory Data Register - MDR
Stores the data that is being processed.

### Program Counterr - PC
Stores the address in RAM of the next instruction.

## Memory:

## Buses:

## Input and Output:
- Cache
- buses
- Clock
- Memory
- buses
- Input and Output