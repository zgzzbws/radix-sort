# radix-sort
To fix the impracticality part of Bucket Sort

It could be really diffcult for Bucket Sort to sort the large integer keys.
In this situation, we can just calculate the radix of each number, and 
sort the digit.

In this program, following parameters are considered:
1. Input Size: N
2. Bucket Numbers: B
3. The Highest Digit: M
4. Number of Passes: P

B here is 10. To lower P and improve the effeciency, it cound be better to set the B = 2^b.
Therein, b+log2(b) = log2(N).
