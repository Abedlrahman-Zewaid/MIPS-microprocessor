# Single-Cycle MIPS Processor

### Overview

This project implements a 32-bit Single-Cycle MIPS Processor in Verilog, based on the architecture from Digital Design and Computer Architecture by David A. Patterson & Sarah L. Harris.

In this design, each instruction (fetch, decode, execute, memory access, and write-back) is executed in a single clock cycle.

### Features

Fully functional MIPS single-cycle processor.

Supports arithmetic, logic, memory, and branch/jump instructions.

Implements datapath + control unit architecture.

Includes standard MIPS modules:

- ALU

- Program Counter (PC)

- Instruction Memory

- Register File

- Data Memory

- Control Unit (main decoder + ALU decoder)

- Supporting blocks (sign extend, shift, adders, multiplexers)

- Runs test programs such as Factorial and Greatest Common Divisor (GCD)

### Architecture

##### The processor is divided into:

- Datapath – executes operations, reads/writes registers, handles memory

- Controller – generates control signals using a main decoder and an ALU decoder
