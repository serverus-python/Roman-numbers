# Roman-numbers
with this project you can convert decimal numbers in roman numbers and vice versa

decimal_to_romans

MDCLXVI

we divide the roman letters in 3 groups. In this way we can translate every digit in a modular way even if it is an unit or a ten.

           i
(M,D,C) <- 1
(C,L,X) <- 2
(X,V,I) <- 3

the index i indiactes the position of the digit, the pointer j is used to compose the new roman digit

I  1     V  5
X  10    L  50
C  100   D  500
