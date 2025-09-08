<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This design implements a Hamming (7,4) encoder and decoder in Verilog.  
The encoder takes 4 data bits and generates a 7-bit code word with 3 parity bits.  
The decoder calculates the syndrome, detects any single-bit error, and corrects it automatically.  

## How to test

Provide a 4-bit input to the encoder.
2. Observe the 7-bit encoded output.
3. Optionally flip one bit to simulate an error.
4. Feed it into the decoder.
5. The decoder outputs the corrected 4-bit data.

## External hardware

List external hardware used in your project (e.g. PMOD, LED display, etc), if any
