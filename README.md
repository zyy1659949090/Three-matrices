# Three-matrices
Three matrices
描述
Chubby Yang is studying linear equations right now. He came up with a nice problem. In the problem you are given an n × n matrix W, consisting of integers, and you should find two n × n matrices A and B, all the following conditions must hold:
Aij = Aji, for all i, j (1 ≤ i, j ≤ n);
Bij =  - Bji, for all i, j (1 ≤ i, j ≤ n);
Wij = Aij + Bij, for all i, j (1 ≤ i, j ≤ n).
Can you solve the problem?

输入
The first line contains an integer n (1 ≤ n ≤ 170). Each of the following n lines contains n integers. The j-th integer in the i-th line is Wij(0 ≤ |Wij| < 1717).
输出
The first n lines must contain matrix A. The next n lines must contain matrix B. Print the matrices in the format equal to format of matrix W in input. It is guaranteed that the answer exists. If there are multiple answers, you are allowed to print any of them.

The answer will be considered correct if the absolute or relative error doesn't exceed 10 - 4.
样例输入
3
1 2 3
4 5 6
7 8 9
样例输出
1.00000000 3.00000000 5.00000000
3.00000000 5.00000000 7.00000000
5.00000000 7.00000000 9.00000000
0.00000000 -1.00000000 -2.00000000
1.00000000 0.00000000 -1.00000000
2.00000000 1.00000000 0.00000000
