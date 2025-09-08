# tt_hamming_code_7x4

## How it works
This design implements a Hamming (7,4) encoder and decoder using Wokwi.  
The encoder takes 4 data bits and generates a 7-bit code word with 3 parity bits.  
The decoder calculates the syndrome, detects any single-bit error, and corrects it automatically.  

## How to test
1. Provide a 4-bit input to the encoder.  
2. Observe the 7-bit encoded output.  
3. Optionally flip one bit to simulate an error.  
4. Feed it into the decoder.  
5. The decoder outputs the corrected 4-bit data.  

## External hardware
None

