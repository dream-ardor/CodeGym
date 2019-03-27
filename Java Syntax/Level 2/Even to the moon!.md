## Even to the moon!
Level 2, Lesson 8

"Amigo, did you know that lunar gravity is about 17% of gravity on Earth?"<br>
"Nope.""<br>
"Neither did I. Now this information will be used a lot. To avoid having to manually calculate it each time, implement a getWeight(int) method that takes a person's body weight on Earth (in newtons), and returns the weight of that person on the moon (in newtons)."<br>
The method should return a double.

Consider this example:<br>
The getWeight method is called with the argument 888.

Example output:"<br>
150.96

Requirements:<br>
1. The getWeight(int) method must be public and static.<br>
2. The getWeight method must return a double."<br>
3. The getWeight method should not display anything."<br>
4. The getWeight method should correctly convert the Earth weight in newtons to the lunar weight, and then return this value."<br>

## My Code
```java
public class Solution {
    public static void main(String[] args) {
        System.out.println(getWeight(888));
    }

    public static double getWeight(int earthWeight) {
     double result = .17 * earthWeight;
     return result;
    }
}
```
