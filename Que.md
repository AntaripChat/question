Taru exam is on the head. So she started learning physics. There she learned about Pascal's law. Now she wanted to try an experiment to get a better understanding of the same.

For, the experiment Taru has N buckets (numbered from 1,2,3...N) which all are initially empty.

She has M number of queries. Each query represents an integer that is of 4 types.

Query 1: Fill all the buckets with water.
Query 2: Empty all even valued buckets (2, 4, 6 ... N).
Query 3: Empty all odd number buckets (1, 3, 5, ... N).
Query 4: Empty all the buckets. (1,2,3...N).
You have to return the number of buckets that are filled after performing M queries.

Input Format

First-line will contain an integer N.
Second-line will contain an Integer M.
Next M lines will contain the query number (1, 2, 3, 4).
Constraints

1 ≤ N ≤ 106
1 ≤ M ≤ 105
Ith query will be in (1, 2, 3, 4).
Empty bucket operation can be done on empty bucket also. Though it will not make in any difference.
Output Format

Output a single integer, denoting the number of buckets that are filled.
Evaluation Parameters

Sample Input
5
3
1
2
2
Sample Output
3
Explanation
Since we have 5 buckets. Initially, by query 1 all buckets get filled. After query 2 only 1, 3, 5 buckets are filled. After query 3 only 3 buckets are filled (i.e. 1, 3, 5). Therefore 3 is the answer.


