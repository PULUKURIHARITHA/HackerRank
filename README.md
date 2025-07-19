# HackerRank
Task
Given an integer, , perform the following conditional actions:

If  is odd, print Weird
If  is even and in the inclusive range of  to , print Not Weird
If  is even and in the inclusive range of  to , print Weird
If  is even and greater than , print Not Weird
Input Format

A single line containing a positive integer, .

Constraints

Output Format

Print Weird if the number is weird. Otherwise, print Not Weird.

Sample Input 0

3
Sample Output 0

Weird
Explanation 0


 is odd and odd numbers are weird, so print Weird.

Sample Input 1

24
Sample Output 1

Not Weird
Explanation 1


 and  is even, so it is not weird.

Language
Python 3
More
124687539
n=int(input())
if n%2!=0:
    print("Weird")
elif 2<=n<=5:
    print("Not Weird")
elif 6<=n<=20:
    print("Weird")
else:
    print("Not Weird")
Line: 1 Col: 1

Test against custom input
Congratulations!

You have passed the sample test cases. Click the submit button to run your code against all the test cases.


Sample Test case 0

Sample Test case 1
Input (stdin)
3
Your Output (stdout)
Weird
Expected Output
Weird

n=int(input())
if n%2!=0:
    print("Weird")
elif 2<=n<=5:
    print("Not Weird")
elif 6<=n<=20:
    print("Weird")
else:
    print("Not Weird")














ANOTHER CODE(FIND THE RUNNER UP SCORE
Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given  scores. Store them in a list and find the score of the runner-up.

Input Format

The first line contains . The second line contains an array   of  integers each separated by a space.

Constraints

Output Format

Print the runner-up score.

Sample Input 0

5
2 3 6 6 5
Sample Output 0

5
Explanation 0

Given list is . The maximum score is , second maximum is . Hence, we print  as the runner-up score.
PROGRAM
if __name__ == '__main__':
    n = int(input())
    arr = map(int, input().split()) 
max_score=set(arr)
max_score=sorted(max_score)
print(max_score[-2])
