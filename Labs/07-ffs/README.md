# Part one: Link to the repository
https://github.com/Simon-Roubal/Digital-electronics-1/edit/main/Labs/07-ffs
# Part two: Characteristic equations and completed tables for D, JK, T flip-flops

![obrazek](https://user-images.githubusercontent.com/77580298/112829861-05b05800-9092-11eb-910e-8210277d2675.png)

| **clk** | **d** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](Images/eq_uparrow.png) | 0 | 0 | 0 | Store |
   | ![rising](Images/eq_uparrow.png) | 0 | 1 | 0 | Store |
   | ![rising](Images/eq_uparrow.png) | 1 | 1 | 1 | Store |
   | ![rising](Images/eq_uparrow.png) | 1 | 0 | 1 | Store |

   | **clk** | **j** | **k** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-: | :-- |
   | ![rising](Images/eq_uparrow.png) | 0 | 0 | 0 | 0 | No change |
   | ![rising](Images/eq_uparrow.png) | 0 | 0 | 1 | 1 | No change |
   | ![rising](Images/eq_uparrow.png) | 0 | 1 | 0 | 0 | Reset |
   | ![rising](Images/eq_uparrow.png) | 0 | 1 | 1 | 0 | Reset |
   | ![rising](Images/eq_uparrow.png) | 1 | 0 | 0 | 1 | Set |
   | ![rising](Images/eq_uparrow.png) | 1 | 0 | 1 | 1 | Set |
   | ![rising](Images/eq_uparrow.png) | 1 | 1 | 0 | 1 | Invert |
   | ![rising](Images/eq_uparrow.png) | 1 | 1 | 1 | 0 | Invert |

   | **clk** | **t** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](Images/eq_uparrow.png) | 0 | 0 | 0 | No change |
   | ![rising](Images/eq_uparrow.png) | 0 | 1 | 1 | No change |
   | ![rising](Images/eq_uparrow.png) | 1 | 0 | 1 | No change |
   | ![rising](Images/eq_uparrow.png) | 1 | 1 | 0 | No change |

# D latch
## VHDL code listing of the process ```p_d_latch```
```vhdl

```
## Listing of VHDL reset and stimulus processes from the testbench ``````tb_d_latch.vhd```
```vhdl

```
## Screenshot with simulated time waveforms

# Flip-flops
## VHDL code listing of the processes ```p_d_ff_arst```, ```p_d_ff_rst```, ```p_jk_ff_rst```, ```p_t_ff_rst```
```vhdl 

```
## Listing of VHDL clock, reset and stimulus processes from the testbench files
```vhdl

```
## Screenshot with simulated time waveforms

# Shift register
## Image of the shift register schematic

