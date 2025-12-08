<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project designs a simple NAND gate, which is the complement of the AND function.
The program involves defining a module using Verilog HDL, with NAND_2 as the identifying name. 
The compiler then creates inputs and outputs using the port list.
The wire Yd referes to a non-port connection.
The "and(Yd, A, B); not(Y,Yd); endmodule;" directly implements the use of an AND gate along with an inverter or NOT gate.
By this, we design a NAND gate.

## How to test
Truth Table for NAND
Inputs | Output A | B | Y 0 0 1 0 1 1 1 0 1 1 1 0


