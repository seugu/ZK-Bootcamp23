
original: https://hackmd.io/D-_zioqNRr-ah08WZFQcIw

Some modular arithmetic

## Questions

1. Working with the following set of Integers S =
{0,1,2,3,4,5,6}
What is
a) 4 + 4
b) 3 x 5
c) what is the inverse of 3 ?
2. For S = {0,1,2,3,4,5,6}
Can we consider 'S' and the operation '+' to be a group ?
3. What is
-13 mod 5 ?
4. Polynomials
For the polynomial x^3 − x^2 + 4x − 12
Find a the positive root ?
What is the degree of this polynomial ?

## Answers

### 1. The set shows us Z<sub>7</sub>. 
a) 4+4 = 8 = 1 (mod 7)
b) 3x5 = 15 = 1 (mod 7)
c) If it is an additional inverse is 4 since 3 + 4 = 7 = 0, where 0 is the unit element of the addition operation. 
Otherwise, you may ask for a multiplicative inverse of 3, which is 5 since 3 x 5 = 15 = 1, where 1 is the unit element of the multiplication operation. 

### 2. S is a group under the addition operation as follows: 

Prelim: We assume that (Z, +) is group where "+" is the ordinary addition.
We show, (S,+<sub>s</sub>) is a group. 

**i. Closure**
(S,+<sub>s</sub>) is close under the +<sub>s</sub> operation. Since it is Z~7~, for all a, b in S, a +<sub>s</sub> b mod 7 in the S. 

**ii. Associativity**
From the closure, a +<sub>s</sub> b = (a + b) mod 7 where + operation is ordinary addition in Z. 
a +<sub>s</sub> (b +<sub>s</sub>  c) = (a + b) + c mod 7 (from (Z, +) is associative ) 
(a + b) + c mod 7 = (a +<sub>s</sub> b) +<sub>s</sub> c therefore (S,+<sub>s</sub>) is also associative.

**iii. Identity Element**
Is there any element a in S, so that for all b in S, a +<sub>s</sub> b is equal b. 
a = 0 

**iv. Each element except the identity(zero), has the inverse under the addition operation.** 
Not elegantly :) 
the inverse of 1 equals 6 since 1 +<sub>s</sub> 6 = 0 <br />
the inverse of 2 equals 5 since 2 +<sub>s</sub> 5 = 0 <br />
the inverse of 3 equals 4 since 3 +<sub>s</sub> 4 = 0 <br />
the inverse of 4 equals 3 since 4 +<sub>s</sub> 3 = 0 <br />
the inverse of 5 equals 2 since 5 +<sub>s</sub> 2 = 0 <br />
the inverse of 6 equals 1 since 6 +<sub>s</sub> 1 = 0 <br />
So each element has its inverse. 

From i, ii, iii, and iv, (S,+<sub>s</sub>) is a group. 

### 3. What is -13 mod 5?

2 

### 4. For the polynomial x<sup>3</sup>-x<sup>2</sup>+4x-12

i. Find a positive root. <br />
x=2, since 2<sup>3</sup>+2<sup>2</sup>+4.2-12 = 8 - 4 + 8 - 12 = 0 <br />
ii. The degree of polynomial is the highest exponent which is 3. 

