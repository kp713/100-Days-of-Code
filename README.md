# 100-Days-of-Code

I've fairly good knowledge of programming in python and Data Science. Through the next hundred days I want to brush up my Python skills, DBMS skills, and also my stats and ML all hands on by coding in Python. This is my Journey. I've decided to start from the basics, and I understand if the challenge very well goes over a 100 days because of all the things I want to learn. This is my journey, starting from Day 1.

# Day 1 : 8th Jan 2022

Starting my HDOC today
Solved for :

There's a staircase with N steps, and you can climb 1 or 2 steps at a time. Given N, write a function that returns the number of unique ways you can climb the staircase. The order of the steps matters.

For example, if N is 4, then there are 5 unique ways:

1, 1, 1, 1
2, 1, 1
1, 2, 1
1, 1, 2
2, 2
What if, instead of being able to climb 1 or 2 steps at a time, you could climb any number from a set of positive integers X? For example, if X = {1, 3, 5}, you could climb 1, 3, or 5 steps at a time. Generalize your function to take in X.


# Day 2 :  9th Jan 2022

Solved for :

Given a list of numbers and a number k, return whether any two numbers from the list add up to k.

For example, given [10, 15, 3, 7] and k of 17, return true since 10 + 7 is 17.

Bonus: Can you do this in one pass?

# Day 3 : 10th Jan 2022

Given an array of integers, return a new array such that each element at index i of the new array is the product of all the numbers in the original array except the one at i.

For example, if our input was [1, 2, 3, 4, 5], the expected output would be [120, 60, 40, 30, 24]. If our input was [3, 2, 1], the expected output would be [2, 3, 6].

Follow-up: what if you can't use division?

Progress : got the idea to do it with and wihtout division in minutes (seconds even) but struggled with the right syntax.

# Day 4 : 11th Jan 2022

To be completely honest from 11th -14th Jan I spent a lot of time programming and coding in my actual workplace wayy over 1 hour a day and on the 16th I spent a good amount of time practicing my SQL skills on Hackerrank and cleared their advanced certification too. I unfortunately didn't save any of the queries and the stuff I do at work can't be documented here. So here I am compensating with 1 problem for each day I couldn't document.

The problem : found in Hackerrank : link : https://www.hackerrank.com/challenges/matrix-script/problem

Neo has a complex matrix script. The matrix script is a  X  grid of strings. It consists of alphanumeric characters, spaces and symbols (!,@,#,$,%,&).

Capture.JPG

To decode the script, Neo needs to read each column and select only the alphanumeric characters and connect them. Neo reads the column from top to bottom and starts reading from the leftmost column.

If there are symbols or spaces between two alphanumeric characters of the decoded script, then Neo replaces them with a single space '' for better readability.

Neo feels that there is no need to use 'if' conditions for decoding.

Alphanumeric characters consist of: [A-Z, a-z, and 0-9].

Input Format

The first line contains space-separated integers  (rows) and  (columns) respectively.
The next  lines contain the row elements of the matrix script.

Constraints


Note: A  score will be awarded for using 'if' conditions in your code.

Output Format

Print the decoded matrix script.

Sample Input 0

7 3
Tsi
h%x
i #
sM 
$a 
#t%
ir!


Sample Output 0

This is Matrix#  %!
Explanation 0

The decoded script is:

This$#is% Matrix#  %!
Neo replaces the symbols or spaces between two alphanumeric characters with a single space   ' ' for better readability.

So, the final decoded script is:

This is Matrix#  %!

I was able to solve for this 
