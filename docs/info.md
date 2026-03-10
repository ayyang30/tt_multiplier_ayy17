<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project is a 4-bit by 4-bit unsigned multiplier built in Verilog. It takes two 4-bit inputs from `ui_in`, multiplies them, and sends the 8-bit product to `uo_out`.

## How to test

Apply two 4-bit values to the input bus, with one operand in the upper 4 bits and the other in the lower 4 bits. The output should match their product, and the testbench verifies this by checking multiple input combinations automatically.

## External hardware

N/a
