# Part One: Link to the repository

https://github.com/Simon-Roubal/Digital-electronics-1/tree/main/Labs/02-logic

# Part Two: Logic table

| **Dec. equivalent** | **B[1:0]** | **A[1:0]** | **B is greater than A** | **B equals A** | **B is less than A** |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 0 | 0 0 | 0 0 | 0 | 1 | 0 |
| 1 | 0 0 | 0 1 | 0 | 0 | 1 |
| 2 | 0 0 | 1 0 | 0 | 0 | 1 |
| 3 | 0 0 | 1 1 | 0 | 0 | 1 |
| 4 | 0 1 | 0 0 | 1 | 0 | 0 |
| 5 | 0 1 | 0 1 | 0 | 1 | 0 |
| 6 | 0 1 | 1 0 | 0 | 0 | 1 |
| 7 | 0 1 | 1 1 | 0 | 0 | 1 |
| 8 | 1 0 | 0 0 | 1 | 0 | 0 |
| 9 | 1 0 | 0 1 | 1 | 0 | 0 |
| 10 | 1 0 | 1 0 | 0 | 1 | 0 |
| 11 | 1 0 | 1 1 | 0 | 0 | 1 |
| 12 | 1 1 | 0 0 | 1 | 0 | 0 |
| 13 | 1 1 | 0 1 | 1 | 0 | 0 |
| 14 | 1 1 | 1 0 | 1 | 0 | 0 |
| 15 | 1 1 | 1 1 | 0 | 1 | 0 |

# Part three: Karnaugh maps and simplified SoP form of the "greater than" function and a PoS form of the "less than" function

## Karnaugh maps

B is greater than A: 

![alt text](https://github.com/Simon-Roubal/Digital-electronics-1/blob/main/Labs/02-logic/pictures/B%20bigger%20than%20A.png?raw=true)

B equals A: 

![alt text](https://github.com/Simon-Roubal/Digital-electronics-1/blob/main/Labs/02-logic/pictures/b%20equals%20to%20a.png?raw=true)

B is less than A: 

![alt text](https://github.com/Simon-Roubal/Digital-electronics-1/blob/main/Labs/02-logic/pictures/b%20smaller%20than%20a.png?raw=true)

## SoP and PoS

\begin{align*}
    SoP(B>A) =&~ (B_{1}\overline{A_{1}}\) + (B_{1}B_{0}\overline{A_{0}}\)+(B_{0}\ \overline{A_{1}}+\ \overline{A_{0}}\)
\end{align*}

\begin{align*}
    SoP(B<A) =&~ (\overline{B_{1}}\ + A_{1}) * (\overline{B_{0}}\ + A_{1}) *(A_{0}+ A_{1})*(\overline{B_{0}}\ + \overline{B_{1}}\) * (\overline{B_{1}}\ + A_{0})
\end{align*}


https://www.edaplayground.com/x/8Qrz

https://www.edaplayground.com/x/8Qrz
