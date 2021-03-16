# Part one: Link to the repository
https://github.com/Simon-Roubal/Digital-electronics-1/tree/main/Labs/05-counter
# Part two: Connection of push buttons on Nexys A7 board
## Table with connection of push buttons
   | **Button** | **Pin** |
   | :-: | :-: |
   | BTNL | P17 |
   | BTNR | M17 |
   | BTNU | M18 |
   | BTND | P18 |
   | BTNC | N17 |
## Table with calculated values
   | **Time interval** | **Number of clk periods** | **Number of clk periods in hex** | **Number of clk periods in binary** |
   | :-: | :-: | :-: | :-: |
   | 2&nbsp;ms | 200 000 | `x"3_0d40"` | `b"0011_0000_1101_0100_0000"` |
   | 4&nbsp;ms | 400 000 | `x"6_1A80"` | `b"0110_0001_1010_1000_0000"` |
   | 10&nbsp;ms | 1 000 000 | `x"F_4240"` | `b"1111_0100_0010_0100_0000"` |
   | 250&nbsp;ms | 25 000 000 | `x"17D_7870"` | `b"0001_0111_1101_0111_1000_0100_0000"` |
   | 500&nbsp;ms | 50 000 000 | `x"2FA_F080"` | `b"0010_1111_1010_1111_0000_1000_0000"` |
   | 1&nbsp;sec | 100 000 000 | `x"5F5_E100"` | `b"0101_1111_0101_1110_0001_0000_0000"` |
# Part three: Bidirectional counter
## VHDL code of the process `p_cnt_up_down`
```vhdl

```
## VHDL reset and stimulus processes from testbench file `tb_cnt_up_down.vhd`
```vhdl

```
## Screenshot with simulated time waveforms

# Part four: Top level
## VHDL code from source `file top.vhd`
```vhdl

```
## Image of the top layer including both counters
