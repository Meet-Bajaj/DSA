# Questions From contest : 6168
---
## 1. Inverse Of Array
 Take as input N, a number. Take N more inputs and store that in an array. Write a recursive function which inverses the array. Print the values of inverted array

**Input Format**
> Enter a number N and take N more inputs
> 
> ***Constraints***
> None
> 
 **Output Format**
> Display the values of the inverted array in a space separated manner
 
**Sample Input**
> 5
> 0 2 4 1 3

**Sample Output**
> 0 3 1 4 2

 **Explanation :** 

> Swap element with index
> for eg : element 4 at index 2 becomes element 2 at index 4
> 
## 2.Array-Target Sum Triplets
Take as input N, the size of array. Take N more inputs and store that in an array. Take as input “target”, a number. Write a function which prints all triplets of numbers which sum to target.

**Input Format**
> First line contains input N.
> Next line contains N space separated integers denoting the elements of the array.
> The third line contains a single integer T denoting the target element.

***Constraints***
>Length of Array should be between 1 and 1000.

**Output Format**
> Print all the triplet present in the array in a new line each. The triplets must be printed as A, B and C where A,B and C are the elements of the triplet ( A<=B<=C) and all triplets must be printed in sorted order. Print only unique triplets.
 
**Sample Input**
> 9
> 5 7 9 1 2 4 6 8 3
> 10

**Sample Output**
> 1, 2 and 7
> 1, 3 and 6
> 1, 4 and 5
> 2, 3 and 5

**Explanation :**
> Array = {5, 7, 9, 1, 2, 4, 6 ,8 ,3}. Target number = 10. Find any three number in the given array which sum to target number.
## 3.Array Linear Search
Take as input N, the size of an array. Take N more inputs and store that in an array. Take another number’s input as M. Write a function which returns the index on which M is found in an array, in case M is not found -1 is returned. Print the value returned.

It reads a number N.
2.Take Another N numbers as an input and store them in an Array.
Take another number M as an input.
If M is found in the Array the index of M is returned else -1 is returned and print the value returned.
**Input Format**
>***Constraints***
>N cannot be Negative. Range of Numbers can be between -1000000000 to 1000000000. M can be between -1000000000 to 1000000000.
>
**Sample Input**
> 5
> 2
> 4
> 6
> 9
> 17
> 17

**Sample Output**
> 4

**Explanation :**
> Given array = {2, 4, 6, 9, 17}. Target number = 17. Index = 4.
## 4. Array-Target Sum Pairs
Take as input N, the size of array. Take N more inputs and store that in an array. Take as input “target”, a number. Write a function which prints all pairs of numbers which sum to target.

**Input Format**
> The first line contains input N. Next N lines contains the elements of array and (N+1)th line contains target number.

***Constraints***
> Length of the arrays should be between 1 and 1000.

**Output Format**
> Print all the pairs of numbers which sum to target. Print each pair in increasing order.

**Sample Input**
> 5
> 1
> 3
> 4
> 2
> 5
> 5

**Sample Output**
> 1 and 4
> 2 and 3

**Explanation :**
> Find any pair of elements in the array which has sum equal to target element and print them.
## 5. Array-Max Value in Array.
Take an input N, the size of array. Take N more inputs and store that in an array. Write a function which returns the maximum value in the array. Print the value returned.

1.It reads a number N.

2.Take Another N numbers as input and store them in an Array.

3.calculate the max value in the array and return that value.

**Input Format**
> First line contains integer n as size of array. Next n lines contains a single integer as element of array.

***Constraints***
> N cannot be Negative. Range of Numbers can be between -1000000000 to 1000000000

**Output Format**
> Print the required output.

**Sample Input**
> 4
> 2
> 8
> 6
> 4
**Sample Output**
> 8

**Explanation :**
> Arrays= {2, 8, 6, 4} => Max value = 8 .
## 6. Pair Of Roses
Deepak has a limited amount of money that he can spend on his girlfriend. So he decides to buy two roses for her. Since roses are of varying sizes, their prices are different. Deepak wishes to completely spend that fixed amount of money on buying roses for her.
As he wishes to spend all the money, he should choose a pair of roses whose prices when summed up are equal to the money that he has.
Help Deepak choose such a pair of roses for his girlfriend.

NOTE: If there are multiple solutions print the solution that minimizes the difference between the prices i and j. After each test case, you must print a blank line.

**Input Format**
>- The first line indicates the number of test cases T.
>- Then, in the next line, the number of available roses, N is given.
>- The next line will have N integers, representing the price of each rose, a rose that costs less than 1000001.
>- Then there is another line with an integer M, representing how much money Deepak has.
>- There is a blank line after each test case.

***Constraints***
> 1≤ T ≤100
> 2 ≤ N ≤ 10000
> Price[i]<1000001

**Output Format**
>For each test case, you must print the message: ‘Deepak should buy roses whose prices are i and j.’, where i and j are the prices of the roses whose sum is equal do M and i ≤ j. You can consider that it is always possible to find a solution. If there are multiple solutions print the solution that minimizes the difference between the prices i and j.
>
**Sample Input**
> 2
> 2
> 40 40
> 80
> 
> 5
> 10 2 6 8 4
> 10

**Sample Output**
> Deepak should buy roses whose prices are 40 and 40.
> Deepak should buy roses whose prices are 4 and 6.
**Explanation :**
Find two such kinds of price of roses which has sum up to equal to Deepak's Money.
## 7. Help Ramu
Ramu often uses public transport. The transport in the city is of two types: cabs and rickshaws. The city has n rickshaws and m cabs, the rickshaws are numbered by integers from 1 to n, the cabs are numbered by integers from 1 to m.

Public transport is not free. There are 4 types of tickets:

A ticket for one ride on some rickshaw or cab. It costs c1 ruppees;
A ticket for an unlimited number of rides on some rickshaw or on some cab. It costs c2 ruppees;
A ticket for an unlimited number of rides on all rickshaws or all cabs. It costs c3 ruppees;
A ticket for an unlimited number of rides on all rickshaws and cabs. It costs c4 ruppees.

Ramu knows for sure the number of rides he is going to make and the transport he is going to use. He asked you for help to find the minimum sum of ruppees he will have to spend on the tickets.

**Input Format**
> Each Test case has 4 lines which are as follows:
> 
> The first line contains four integers c1, c2, c3, c4 (1 ≤ c1, c2, c3, c4 ≤ 1000) — the costs of the tickets.
> The second line contains two integers n and m (1 ≤ n, m ≤ 1000) — the number of rickshaws and cabs Ramu is going to use.
> The third line contains n integers ai (0 ≤ ai ≤ 1000) — the number of times Ramu is going to use the rickshaw number i.
> The fourth line contains m integers bi (0 ≤ bi ≤ 1000) — the number of times Ramu is going to use the cab number i.
> 
***Constraints***
> 1 <= T <= 1000 , where T is no of testcases
> 1 ≤ c1, c2, c3, c4 ≤ 1000
> 1 ≤ n, m ≤ 1000
> 0 ≤ ai , bi ≤ 1000

**Output Format**
> For each testcase , print a single number - the minimum sum of rupees Ramu will have to spend on the tickets in a new line.
> 
**Sample Input**
> 2
> 1 3 7 19
> 2 3
> 2 5
> 4 4 4
> 4 3 2 1
> 1 3
> 798
> 1 2 3

**Sample Output**
> 12
> 1

**Explanation :**
> - For the first testcase ,
> - The total cost of rickshaws = min( min(2 * 1, 3) + min(5 * 1, 3), 7) = min(5, 7) = 5
> - The total cost of cabs = min( min(4 * 1, 3) + min(4 * 1, 3) + min(4 * 1, 3) , 7) = min ( 9, 7) = 7
> - Total final cost = min( totalCabCost + totalRickshawCost , c4) = min( 5 + 7, 19) = min ( 12, 19) = 12
> - We print 12.
## 8. Array-Reverse of Array
Take as input N, the size of array. Take N more inputs and store that in an array. Write a function that reverses the array. Print the values in reversed array.

1.It reads a number N.
2.Take Another N numbers as input and store them in an Array.
3.Reverse the elements in the Array.
4.Print the reversed Array.

**Input Format**
> - First-line contains a single integer n denoting the size of the array.
> - Next, N line contains a single integer denoting the elements of the array.

***Constraints***
> N cannot be Negative. Range of Numbers can be between -1000000000 to 1000000000.

**Output Format**
> Print the elements of the reversed array

**Sample Input**
> 5
> 0
> 4 
> 6 
> 8 
> 9

**Sample Output**
> 9 
> 8 
> 6 
> 4 
> 0 

**Explanation :**
> In the sample case , arr=[0,4,6,8,9] is reversed to arr=[9,8,6,4,0].
## 9. Square Of sorted Array
Given an integer array nums sorted in non-decreasing order, return an array of the squares of each number sorted in non-decreasing order.

**Input Format**
> First line of input contains an integer n representing the length of array n. Next line contains n array elements.

***Constraints***
> 1 <= nums.length <= 10^4
-10^4 <= nums[i] <= 10^4
nums is sorted in non-decreasing order.

**Output Format**
> A sorted array representing squares of elements of nums array.

**Sample Input**
> 5
> -4 -1 0 3 10

**Sample Output**
> 0 1 9 16 100

**Explanation :**
> After squaring, the array becomes [16,1,0,9,100]. After sorting, it becomes [0,1,9,16,100].
## 10. Sort Just Zeroes And once
Sort just 0 and 1

**Input Format**
> A line containing N number of 0s and 1s Next line follows a long sequence of 0 and 1 seperated by space

***Constraints***
> N will not exceed 10^7

**Output Format**
> Sorted Sequence

**Sample Input**
> 7
> 1 0 0 1 1 0 1

**Sample Output**
>0 0 0 1 1 1 1 
## 11. Calculate The Sums
Raj is a very smart kid who recently started learning computer programming. His coach gave him a cyclic array A having N numbers, and he has to perform Q operations on this array. In each operation the coach would provide him with a number X. After each operation, every element of the cyclic array would be replaced by the sum of itself and the element lying X positions behind it in the cyclic array. All these replacements take place simultaneously. For example, if the cyclic array was [a, b, c, d], then after the operation with X = 1, the new array would be [a+d, b+a, c+b, d+c]. He needs to output the sum of the elements of the final array modulus 10^9+7. He made a program for it but it's not very efficient. You know he is a beginner, so he wants you to make an efficient program for this task because he doesn't want to disappoint his coach.

**Input Format**
> The first line of each test file contains a integer N. The next line contains N space separated integers which represent the elements of the cyclic array. The third line contains a integer Q representing the number of operations that will be applied to the array. Finally, Q lines follow, each one containing an integer X .

***Constraints***
> 1 <= N <= 100000
> 1 <= Ai<= 10^9
> 0 <= Q <= 1000000
> 0 <= X < N

**Output Format**
> Your program should output to the standard output stream the sum of the elements of the final array modulus 10^9+7.

**Sample Input**
> 5
> 1 2 3 4 5
> 2
> 1
> 0

**Sample Output**
> 60

**Explanation :**
> - After the 1st operation (X = 1), the array would be [1+5, 2+1, 3+2, 4+3, 5+4] =[6, 3, 5, 7, 9]
> - After 2nd operation (X = 0), the array would be [6+6, 3+3, 5+5, 7+7, 9+9] =[12, 6, 10, 14, 18]
> - Thus the correct answer would equal to = (12+6+10+14+18) % (10^9+7) = 60.
## 12. Bubble Sorting 
Take as input N, the size of array. Take N more inputs and store that in an array. Write a function that bubble sorts the array. Print the elements of sorted array.

1.It reads a number N.
2.Take Another N numbers as input and store them in an Array.
3.Bubble sort the array and print the Array.

**Input Format**
> .

***Constraints***
> N cannot be Negative. Range of Numbers can be between -1000000000 to 100000000.

**Output Format**
> .

**Sample Input**
> 4
> 2
> -18
> 45
> 30

**Sample Output**
>-18
>2
>30
>45

**Explanation :**
> For each test case write bubble sorting program to sort the elements of the array.
## 13. Selection Sorting
Take as input N, the size of array. Take N more inputs and store that in an array. Write a function that selection sorts the array. Print the elements of sorted array.

1. It reads a number N.
2. Take Another N numbers as input and store them in an Array.
3. Sort the array using Selection Sort and print that Array.

**Input Format**
***Constraints***
> N cannot be Negative. Range of Numbers can be between -1000000000 to 1000000000.

**Output Format**
**Sample Input**
> 4
> 2
> -18
> 45
> 30

**Sample Output**
> -18
> 2
> 30
> 45

**Explanation :**
>Write selection sort to sort the given integers in the problem.
## 14. Insetion Sorting
Given an array A of size N , write a function that implements insertion sort on the array. Print the elements of sorted array.

**Input Format**
> First line contains a single integer N denoting the size of the array. Next line contains N space seperated integers where ith integer is the ith element of the array.

***Constraints***
> 1 <= N <= 1000
> |Ai| <= 1000000

**Output Format**
> Output N space seperated integers of the sorted array in a single line.

**Sample Input**
> 4
> 3 4 2 1

**Sample Output**
> 1 2 3 4

**Explanation :**
> For each test case, write insertion sort to sort the array.
## 15.Sort in Linear time
You will be given an array containing only 0s, 1s and 2s. you have sort the array in linear time that is O(N) where N is the size of the array.

**Input Format**
> The first line contains N, which is the size of the array. The following N lines contain either 0, or 1, or 2.

***Constraints***
> 1 <= N <= 10^6
> Each input element x, such that x ∈ { 0, 1, 2 }.

**Output Format**
> Output the sorted array with each element separated by a newline.

**Sample Input**
> 5
> 0
> 1
> 2
> 1
> 2

**Sample Output**
> 0
> 1
> 1
> 2
> 2
## 16. Maximum Sum Path in Two Array
You are provided two sorted arrays. You need to find the sum of the maximum sum path to reach from beginning of any array to end of any of the two arrays. You can switch from one array to another array only at common elements.
link
![example](https://assets.leetcode.com/uploads/2020/07/16/sample_1_1893.png)

**Input Format**
> First line contains integer t which is number of test case. For each test case, it contains two integers n and m which is the size of arrays and next two lines contains n and m space separated integers respectively.

***Constraints***
> 1<=t<=100 1<=n,m, nums1[i], num2[i]<=100000

**Output Format**
> Print the maximum path Sum.

**Sample Input**
> 2
> 8 8
> 2 3 7 10 12 15 30 34
> 1 5 7 8 10 15 16 19
> 5 4
> 2 4 5 8 10
> 4 6 8 9

**Sample Output**
> 122
> 30

**Explanation :**
> Test Case1 **Explanation :** :- 122 is sum of 1, 5, 7, 8, 10, 12, 15, 30, 34
## 17.Maximum Circular Sum
Given a circular integer array nums of length n, return the maximum possible sum of a non-empty subarray of nums.

A circular array means the end of the array connects to the beginning of the array. Formally, the next element of nums[i] is nums[(i + 1) % n] and the previous element of nums[i] is nums[(i - 1 + n) % n].

**Input Format**
> - First line contains integer t which is number of test case.
> - For each test case, it contains an integer n which is the size of array and next line contains n space separated integers denoting the elements of the array.

***Constraints***
> 1<=t<=100
> 1<=n<=1000
> |Ai| <= 10000

**Output Format**
> Print the maximum circular sum for each testcase in a new line.

**Sample Input**
> 1
> 7
> 8 -8 9 -9 10 -11 12

**Sample Output**
> 22

**Explanation :**
> Maximum Circular Sum = 22 (12 + 8 - 8 + 9 - 9 + 10)
## 18. Product of Array Except Self
Given an array arr of n integers where n > 1, return an array output such that output[i] is equal to the product of all the elements of arr except arr[i].

Challenge : do this without division in linear time

**Input Format**
> - First line contains integer N as size of array.
> - Next line contains a N integer as element of array. The product of any prefix or suffix of arr is NOT guaranteed to fit in a 32-bit integer.

***Constraints***
> -10000000 < arr[i]<=10000000

**Output Format**
> Print output array

**Sample Input**
> 4
> 1 2 3 4

**Sample Output**
> 24 12 8 6 
## 19. Running Sum of Array
Given an array nums of length n. We define a running sum of an array as for every index runningSum[i] = sum(nums[0]…nums[i]).

Return the running sum of array for each i (0 <= i < n).

**Input Format**
> First line contains an integer n representing number of elements. Next line contains n integers denoting array elements.

***Constraints***
> 1 <= nums.length <= 1000
> -10^6 <= nums[i] <= 10^6

**Output Format**
> An integer representing running sum array of the given array

**Sample Input**
> 4
> 1 2 3 4

**Sample Output**
> 1 3 6 10

**Explanation :**
> Running sum is obtained as follows: [1, 1+2, 1+2+3, 1+2+3+4].
## 20. Von Neuman Loves Binary
Given a binary number ,help Von Neuman to find out its decimal representation. For eg 000111 in binary is 7 in decimal.

**Input Format**
> The first line contains N , the number of binary numbers. Next N lines contain N integers each representing binary represenation of number.

***Constraints***
> N<=1000 Digits in binary representation is <=16.

**Output Format**
> N lines,each containing a decimal equivalent of the binary number.

**Sample Input**
>4
>101
>1111
>00110
>111111

**Sample Output**
> 5
> 15
> 6
> 63

**Explanation :**
> For binary number fedcba , Decimal number = f * 25 + e * 24 + d * 23 + …..+ a * 20.
## 21. Rain Water Trapping
You are given an input array whose each element represents the height of a line towers. The width of every tower is 1. It starts raining. Water is filled between the gap of towers if possible. You need to find how much water filled between these given towers.

Example :
![example](https://i.imgur.com/m4hyHPw.png)

**Input Format**
> The first line consists of number of test cases T. Each test case consists an integer N as number of towers and next line contains the N space separated integers.

***Constraints***
> 1 <= N <= 1000000 1 <= t <= 10 0 <= A[i] <= 10000000

**Output Format**
> Print how much unit of water collected among towers for each test case.

**Sample Input**
> 2
> 6
> 3  0  0  2  0  4
> 12
> 0  1  0  2  1  0  1  3  2  1  2  1

**Sample Output**
> 10
> 6
## 22. Majority Element
Given an array of size n, find the majority element. The majority element is the element that appears more than n/2 times.

You may assume that the array is non-empty and the majority element always exist in the array.

**Input Format**
> First line contains integer N (size of the array) followed by N more integers.

***Constraints***
**Output Format**
> Majority Element of array

**Sample Input**
> 3
> 1 1 2

**Sample Output**
> 1

**Explanation :**
> Number of 1's in the array is more than 3/2 , Hence majority element is 1
## 23. Next Permutation
Given an array Arr[], Treat each element of the array as the digit and whole array as the number. Implement the next permutation, which rearranges numbers into the numerically next greater permutation of numbers.

If such arrangement is not possible, it must be rearranged as the lowest possible order ie, sorted in an ascending order.

Note: The replacement must be in-place, do not allocate extra memory.

**Input Format**
> - The First Line contains the Number of test cases T.
> - Next Line contains an Integer N, number of digits of the number.
> - Next Line contains N-space separated integers which are elements of the array 'Arr'.

***Constraints***
> 1 <= T <= 100
> 1 <= N <= 1000
> 0 <= Ai <= 9

**Output Format**
> Print the Next Permutation for each number separated by a new Line.

**Sample Input**
> 2
> 3
> 1 2 3 
> 3
> 3 2 1

**Sample Output**
> 1 3 2
> 1 2 3

**Explanation :**
> - Possible permutations for {1,2,3} are {1,2,3} , {1,3,2} , {2,1,3} , {2,3,1}, {3,1,2} and {3,2,1}. {1,3,2} is the immediate next permutation after {1,2,3}.
> - For the second testcase , {3,2,1} is the last configuration so we print the first permutation as its next permutation.
## 24. Nobita Scoreas Good Marks
![just fun](https://i.pinimg.com/600x315/d5/ea/d8/d5ead8ca5652f82c9b20b6f4df2bce59.jpg)
Nobita scored good marks in his previous test, so his mom gave him x candies. Now, he wants to distribute the candies amongst his n friends(including himself).
He wants to distribute the candies equally for which he can either ask her mom for more candies or can return her extra candies.

He will do this in such a way that the number of candies that he takes or returns to his mom is minimum. Can you help him?

**Input Format**
> - First line contains an integer T-denoting the number of test cases.
> - Next T lines contain two space separated integer x and n.

***Constraints***
> 1 <= T <= 10^5
> 1 <=x,n <=10^9

**Output Format**
> Print a single integer equal to minimum candies returned.

**Sample Input**
> 3
> 14 4
> 12 4
> 10 3

**Sample Output**
> 2
> 0
> 1

**Explanation :**
> - In the 1st test case, Nobita can return 2 candies to his mom and then left with 12 candies that can be divided amongst his 4 friends(including him as well), each will get 3 candies each.
> - In 2nd test case , candies are already divisible by 4(Number of Friends). Hence the answer is 0.
> - In 3rd test case , he will return 1 candy and left with 9 candies that can be distributed. Hence the answer in this case is 1.
## 25. How Many Questions
Three close friends, Petya, Vasya, and Tonya, have formed a team to participate in programming contests. The contest organizers offer several problems for the participants to solve. Prior to the contest, the friends agreed that they would only implement a problem's solution if at least two of them are confident in solving it. If not, they would not attempt to solve the problem. For each of the n problems offered in the contest, the friends have information about which of them are confident in solving it. We need to help the friends determine how many problems they will solve based on this information.

**Input Format**
> The given input has 'n' number of problems (where 1 ≤ n ≤ 1000) in a contest. Each problem is represented on a separate line with three integers, either 0 or 1. The first integer denotes Petya's confidence in the problem's solution. 1 indicates that Petya is sure about the solution, while 0 indicates that Petya is not sure. The second integer represents Vasya's opinion on the solution, where 1 means Vasya is sure about the solution, and 0 means he is not sure. The third integer represents Tonya's opinion on the solution, where 1 means Tonya is sure about the solution, and 0 means she is not sure. All the integers in a line are separated by a space.
> 
***Constraints***
> 1 ≤ n ≤ 1000

**Output Format**
> Print a single integer — the number of problems that will be solved

**Sample Input**
> 10
> 1 0 1
> 1 0 0
> 1 0 0
> 1 0 1
> 0 0 0
> 1 0 1
> 1 1 0
> 0 1 1
> 0 1 0
> 0 1 1

**Sample Output**
> 6

**Explanation :**
> There is only 6 questions on which atleast 2 of the three contestants agree. They are question no 1,4,6,7,8,10
## 26. Watermelon Splitting
Pete and his friend Billy went to buy a watermelon on a hot summer day. After weighing the watermelon, which showed w kilos, they decided to divide it. However, they faced a problem because they both prefer even numbers and want each part to weigh an even number of kilos. The two parts do not have to be equal, but they must be positive. Can you help them find out if it's possible to divide the watermelon the way they want? They are exhausted and eager to start their meal as soon as possible.

**Input Format**
> The first (and the only) input line contains integer number w (1 ≤ w ≤ 100000) — the weight of the watermelon bought by the boys.

***Constraints***
> 1 ≤ w ≤ 100000

**Output Format**
> Print YES, if the boys can divide the watermelon into two parts, each of them weighing even number of kilos; and NO in the opposite case.

**Sample Input**
> 8

**Sample Output**
> YES

**Explanation :**
> The watermelon weighing 8 kgs can be split in any of the following ways:
> 1) Pete: 2, Billy: 6
> 2) Pete: 4, Billy: 4
> 3) Pete: 6, Billy: 2
 ## 27. Alex Goes Shopping
 It is Alex’s birthday and she wants to go shopping. She only has ‘A’ units of money and she wants to spend all of her money. However, she can only purchase one kind of item. She goes to a shop which has ‘n’ types items with prices A0,A1,A2,…,An-1. The shopkeeper claims that he has at least ‘k’ items she can choose from. Help her find out if the shopkeeper is correct or not.

**Input Format**
> The first line contains an integer ‘n’ denoting the number of items in the shop. The second line contains ‘n’ space-separated integers describing the respective price of each item. The third line contains an integer ‘q’ denoting the number of queries. Each of the subsequent lines contains two space-separated integers ‘A’ and ‘k’

*****Constraints*****
> 1 <=n, Ai, A <= 105 where 0<=i
> 
> 1 <= q <= 2*n
> 1 <= k <= n
> The array may contain duplicate elements.

**Output Format**
> For each query, print Yes on a new line if the shopkeeper is correct; otherwise, print No instead.

**Sample Input**
> 4
> 100 200 400 100
> 6
> 100 2
> 200 3
> 500 4
> 600 4
> 800 4
> 1200 1

**Sample Output**
> Yes
> Yes
> No
> No
> Yes
> Yes

 **Explanation :**
> In query 1, Alex has 100 units of money. The shopkeeper claims that she can choose to buy from 2 kinds of items i.e. item 1 and item 4 each priced at 100.
> 
> In query 2, The shopkeeper claims that she can choose to buy from 3 kinds of items ie item 1 and item 4 each priced at 100(she can buy 1 from either of the two), or item 2 priced at 200(she can buy one)
> 
> In query 3, she has 500 units of money. She can either buy item 1 or item 4 ( 5 of each kind respectively). Thus, she has only 2 kinds of items to choose from.
> 
> In query 5, she has 800 units of money. She can either buy item 1 or item 4 ( 8 of each kind respectively) or item 2(she can buy 4 of these) or item 3(2 of these). Thus, she has 4 kinds of items to choose from.
> 
> In query 6, she has 1200 units of money. She can either buy item all types of items to use up her money. Thus, she has 4 kinds of items to choose from. As Shopkeeper as at least 1. Shopkeeper is Correct

