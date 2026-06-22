# half_adder_verification
Verilog implementation and functional verification of a 1-bit Half Adder using a testbench and simulation waveforms.
## files
 - half_adder.v : Adder design
 - half_adder_tb.v : Testbench
 - waveform/half_adder.vcd
 - README.md
## Simulation tools
 - EDA playground
 - Icarus Verilog
## Inputs:
- a
- b
## Outputs:
- sum
- carry
## Truth Table
 | a | b | sum | carry |
 |---|---|-----|-------|
 | 0 | 0 |  0  |   0   |
 | 0 | 1 |  1  |   0   |
 | 1 | 0 |  1  |   0   |
 | 1 | 1 |  0  |   1   |

 ## Boolean equations
 - sum = a^b
 - carry = a&b

## Author
  Apoorva B A
