## Homework 2

1. Modular arithmetic - you just need to find examples, you don't need to prove anything.
 
1.1. Is it true that all odd squares are ≡ 1 (mod 8) ?
 
Let assume that n = (2k+1) k in Z, n is odd. If we take the square of n<sup>2</sup>, (2k+1)<sup>2</sup> = 4k<sup>2</sup>+4k+1= 4k(k+1)+1 = 1 mod 8 since k is odd, k+1 is even and 4k(k+1) will be equal 0.  

1.2. what about even squares (mod 8) ?

Let assume n is even so n = 2k, k can be even or odd. n<sup>2</sup> =(2k)<sup>2</sup> =4k<sup>2</sup> if k is odd, k<sup>2</sup>2 is odd, and vice versa. 

First, k<sup>2</sup> odd so k<sup>2</sup>=2m+1, so 4k<sup>2</sup> = 4(2m+1) = 4m+1 = 1 mod 8


Otherwise, k<sup>2</sup> is even so k<sup>2</sup>=2m, 4k<sup>2</sup> = 4(2m) = 0 mod 8. Consequently, it can be 0 or 1. 

2. Try out the vanity bitcoin address example at asecurity or the Ethereum version.
3. What do you understand by<br />

    1. O(n): Linear time, It means if your input doubled, your execution time or output size doubled. <br />
    2. O(1): Constant time, It means the output size or execution time doesn't depend on the input. O(1) is The best. <br />
    3. O(log n): Logarithmic time, It means there is a bound for your execution or input size. <br />


For a proof size, which of these would you want?
Of course, O(1). Who wants to receive a big-size proof and wait so long? 

