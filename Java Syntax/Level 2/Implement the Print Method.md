## Implement the print method
### Level 2, Lesson 1

In the print method, display the passed string 4 times. Each time, on a new line.

Requirements:
```
1. The program should display text on the screen.
2. The main method should not call System.out.println or System.out.print.
3. The print method should display the text on the screen.
4. The main method should call the Solution class's print method exactly twice.
5. The print method should display the string 4 times. Each time, on a new line.
```

## My Code
```java
public class Solution {
    public static void main(String[] args) {
        print("Java is easy to learn!");
        print("Java opens many opportunities!");
    }

    public static void print(String s) {
      System.out.println(s);
      System.out.println(s);
      System.out.println(s);
      System.out.println(s);
        //write your code here
    }
}

```
