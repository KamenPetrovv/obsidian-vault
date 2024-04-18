### Polynomials
Polynomials - Многочлени - Sum of monomials
Term (monomial) - член
$$ \sum_{ i = 0 }^{d} {a_ix^i}$$
Numpy has a class that let's us work with polynomials:
```
import numpy.polynomial.Polynomial as poly
```
or 
```
from numpy.polynomial import Polynomial
```
This way we can use the class without using its module every time we need to use it

There are 2 ways to represent polynomials in Numpy:
1. The old way:
		`np.poly1d([1, 2, 3])` Represents: $x^2 + 2x + 3$
2. The preferred way 
		`Polynomial([1, 2, 3])` Represents: $1 + 2x + 3x^2$
		
![[Pasted image 20240417161544.png]]

Simply put the order of the params is reversed. The better way is to start with the smallest power of X. 

For me the old way seems more intuitive because I am used to seeing the polynomial starting from the highest power but w/e.

Ok ok ... The new way is better for coding because arrays start from index 0 and it relates perfectly with the term's power.
![[Pasted image 20240417161928.png]]
The term's power is the index of the array of the coefficients.

A polynomial with X substituted with 10,2 or 16 makes the decimal, binary and hexadecimal counting systems $132 = 1*10^2 + 3*10^1 + 2*10^0$