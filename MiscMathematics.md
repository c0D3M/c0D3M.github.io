## Modular Multiplicaative Inverse
## Chinese Remainder Theorem
Smallest number which when divided by x, y, z leaves remainder a, b, c

Example:
Find smallest number when divided by 2, 3, 5 leaves remainder 1, 2, 3
x = 15x1 + 10x2 + 6x3 [15x1 comes from the fact that it is not divisible by 2 but by 3,5 that means its a multiple of 3 and 5 i.e. 15]

lowest 15x1 when divided by 2 leaves remainder 1 = 1
lowest 10x2 when divided by 3 leaves remainder 2 = 2
lowest 6x3  when divided by 5 leaves remainder 3 = 3

15 + 20 + 18 = 53 
But is this the smallest ? we can find by lcm(2,3,5) = 30 
Since divided by 30 doesnt change the result 
53-30 = 23 , so thats the smalles number satisfying the above condition

Example
Find smallest number when divided by 7, 9, 11 leaves remainder 1, 2, 3

x = 99x1 + 77x2 + 63x3

lowest 99x1 when divided by 7 leaves remainder 1 = 1 [ write as multiple of 7 i.e. 98 + 1 / 7]
lowest 77x2 when divided by 9 leaves remainder 2 = 4  [ 72 + 5 / 9..that means we have to find multiple of 5 when divided by 9 leaves remainder 2]
lowest 63x2 when divided by 11 leaves remainder 3= 10   [55 + 8/11 that means we have to find multiple of 8 when divided by 11 leaves remainder 3 ]

x = 99 + 77*4 + 10*63 = 1037

Again check if this is smallest? 
Find LCM of 7, 9 11 = 693
1037 - 693 = 344
Ans 344
