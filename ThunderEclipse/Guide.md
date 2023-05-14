# ThunderEclipse CPUs


## About
Common CPU Architecture built onto FPGAs and CPLDs, with different designs for specific uses and processing requirements. All CPUs use a common socketing syste that ensures they are compatible with the same motherboard where possible. See the CPU Socket folder for the current socket designs.

## Features
  - 

## Files
  - Each CPU has a folder, which contains a .zip archive file of the Quartus II project files needed to build the CPU programming files

# Programming Guide
  - WARNING! DO THIS AT YOUR OWN RISK!
  - Requires Altera (Intel)'s Quartus II software. I use 13.1, but I don't know what versions will and won't work. 

## Assembler and Compiler
There are 3 levels of language that can be used to program for the CPU. They are:

  - ThunderEclipse Assembly  (just the opcode and operand, with comments. Nothing else supported)
  - ThunderEclipse Low Level (Essentially asssembly but with some memory management e.g. variables and functions)
  - ThunderEclipse Mid Level (feels not too disimilar to an unpolished c-style language, but with support for low level functions)

It's recommended to program in ThunderEclipse Mid Level, since it's the most intiuive by far and also doesn't requrie understanding of the architecture of the CPU. Libraries which need to be as fast as possible, e.g. the PBI and GPU library are programmed in low level.
