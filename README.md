# Algorithm - Fibonacci Number with  top-down and bottom-up methods
Using top-down ( divide and conqure/ pure recursive)  and bottom-up  (dynamic-programming-like) methods to calculate the n-th Fibonacci Number, denoted as F(n).
There are two files.

## 題目說明和做法 Subject and Statement
### File #1, named as "count2". 
The request as follow "Write code to measure the execution time of F(1), F(2), ..., F(100) using both methods. Plot the results as a line chart. (if your program crashes during computation F(n+1) or takes too much time (>12hours) to compute one value, you can just stop and report the maximum value of n.)".

分別使用top-down( divide and conqure/ pure recursive)和bottom-up (dynamic-programming-like)去計算費式數列從F(1)到F(100)兩種方法所需時間。使用top-down的時間複雜度(time complexicity)是O(2^n)呈現指數成長。因應題目要求若執行時間大於12小時則停止且回報。在我的電腦中執行到F(56)將會是12小時，因此將迴圈設定為range(1,57)。使用Bottom-up method的時間幾乎為0，呈現水平線。

The result will be as image as below 執行時間結果比較圖&darr;&darr;
![image](https://github.com/amberyliang/Algorithm/blob/main/fibonacci_execution_time.png)

### File #2, named as "F(4)".
The request as follow "Let's measure the degree of overlapping subproblem. Calculate the times are F(4) computed when we compute F(5),F(6),.....,F(50). Plot the results into line chart." 

使用top-down方法計算從F(5)到F(50)中F(4)被使用的次數。

The result will be as image as below 執行時間結果比較圖&darr;&darr;

![image](https://github.com/amberyliang/Algorithm/blob/main/Figure_1.png)
