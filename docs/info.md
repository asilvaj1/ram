<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

It is a 4 bit RAM. This example describes a 4-bit x 8-bit single-port RAM design with common read and write addresses in Verilog HDL. Synthesis tools can detect single-port RAM layouts in HDL code and automatically infer altsyncram or altdpram megafunctions, depending on the architecture of the target device.

## How to test

It is tested with 4 inputs, the clock, the write enable input and the 4-bit input data, the output is 4 bits as well.  

  Inputs: ui[3:0] Memory entry address and ui[7:4] Memory input data
  Outputs: uo[3:0] Memory output data
  Bidirectional pins: uio[0]: RAM write enable input

## External hardware

The chip may need a Microcontroller, Raspberry, Arduino or FPGA for data inputs and memory addresses or 8 switches can be placed for data inputs and memory addresses.
