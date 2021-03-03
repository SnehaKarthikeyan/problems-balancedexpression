# projects-balancedexpression

Question:

Mani doesn’t know whether the bracket in an expression is balanced or not. Develop a coding to help him to find the expression is balanced or not.

Input Description:

A string of length <=10000.

Output Description:

Print YES or NO.

Hints:
 
Check if the expression contains both open and close parenthesis for a balanced expression

Sample Input:

{([{}])}[]

Sample Output:

YES

Explanation:

As the bracket is balanced, the output is YES.


Testcase 1:

Input:

([())]{}][){}

Output:

No

Testcase 2:

Input:

{([()]){}{}[{()}]}


Output:

YES

Testcase 3:

Input:

([([()])][{}{}][[{()}]])

Output:

YES

Testcase 4:

Input:

{[{}{}][[{()}]]{()(}]}

Output:
NO

Testcase 5:

Input:

([(){}}]([](){[]()}{})

Output:

No
