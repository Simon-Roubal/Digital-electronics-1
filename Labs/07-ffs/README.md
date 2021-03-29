# Part one: Link to the repository
https://github.com/Simon-Roubal/Digital-electronics-1/edit/main/Labs/07-ffs
# Part two: Characteristic equations and completed tables for D, JK, T flip-flops

<!--
\begin{align*}
    q_{n+1}^D =&~ \\
    q_{n+1}^{JK} =&\\
    q_{n+1}^T =&\\
\end{align*}-->

| **clk** | **d** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](Images/eq_uparrow.png) | 0 | 0 |  |  |
   | ![rising](Images/eq_uparrow.png) | 0 | 1 |  |  |
   | ![rising](Images/eq_uparrow.png) | 1 |  |  |  |
   | ![rising](Images/eq_uparrow.png) | 1 |  |  |  |

   | **clk** | **j** | **k** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-: | :-- |
   | ![rising](Images/eq_uparrow.png) | 0 | 0 | 0 | 0 | No change |
   | ![rising](Images/eq_uparrow.png) | 0 | 0 | 1 | 1 | No change |
   | ![rising](Images/eq_uparrow.png) | 0 |  |  |  |  |
   | ![rising](Images/eq_uparrow.png) | 0 |  |  |  |  |
   | ![rising](Images/eq_uparrow.png) | 1 |  |  |  |  |
   | ![rising](Images/eq_uparrow.png) | 1 |  |  |  |  |
   | ![rising](Images/eq_uparrow.png) | 1 |  |  |  |  |
   | ![rising](Images/eq_uparrow.png) | 1 |  |  |  |  |

   | **clk** | **t** | **q(n)** | **q(n+1)** | **Comments** |
   | :-: | :-: | :-: | :-: | :-- |
   | ![rising](Images/eq_uparrow.png) | 0 | 0 |  |  |
   | ![rising](Images/eq_uparrow.png) | 0 | 1 |  |  |
   | ![rising](Images/eq_uparrow.png) | 1 |  |  |  |
   | ![rising](Images/eq_uparrow.png) | 1 |  |  |  |

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

