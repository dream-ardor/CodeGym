## Java Syntax (Level 2, Lesson 2)
## Pay Raise
In the public static void hackSalary(int a) method, increase the salary by 1000 and display the following: "Your salary is: <a+1000> dollars per month."

where <a+1000> is the salary increased by 1000.

Example output for a = 8000:
Your salary is: 9000 dollars per month.


### Requirements:
```
 1. The program should display text on the screen.
 2. The main method should not call System.out.println or System.out.print.
 3. The hackSalary method should not return a result.
 4. The main method should call the hackSalary method only once.
 5. The hackSalary method should increase the input parameter by 1000 and output text to the screen according to the specified template.
 ```
## My Code
```java
package com.codegym.task.task02.task0205;

/* 
Pay raise

*/
public class Solution {
    public static void main(String[] args) {
        hackSalary(7000);
    }

    public static void hackSalary(int a) {
       a = a + 1000;
       System.out.println("Your salary is: "+ a + " dollars per month.");//write your code here
    }
}

```
