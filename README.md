# Stack-Based-MIPS-Processor

This project implements a stack-based processor with multi-cycle architecture.

## Instructions
- **Arithmetic/Logical Instructions**: add, sub, and, not
- **Memory Reference Instruction**: push, pop
- **Control Flow Instructions**: jmp, jz


In this setup, a unified memory is used for both instructions and data. Instructions are stored in the upper section of memory (first 7 indexes), while data is stored in the lower section (last 4 indexes).
