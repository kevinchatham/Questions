Please review the rules and choose to answer any one of the three problems below. 

## Rules

1. Use Java to build and execute solution. 
     - If you are more comfortable with another language please let us know.
1. Use the editor you are comfortable with.
     - We want to see how you work daily.
1. Communicate your ideas as you go.
     - We want to know your thought process. 
1. Search engines are allowed.
     - Being able to search effectively is a valued skill. 
1. You must share your screen at all times.

Additionally:

- You will have 30 minutes to review the problem, implement a solution, and review results. 

     - Another 10 minutes may be granted if you are close to finishing at the 30 minute mark. 

- Timer starts after you choose the problem you want to solve.

## Problems

### #1 Sum Checker

Write and consume a method that checks an array of numbers to determine if there is at least on pair of numbers whose sum equals the target.

Example
```java
public static void main(){
    final int[] input = { 1, 2, 3, 4 };
    final int target = 5;
    
    // This is true because the pair (1,4) sums to five.
    final Boolean matches = matchingPair(input, target); 
}

public static Boolean matchingPair(int[] input, int target) {
    ...
}

```

### #2 Fizz Buzz

Write a program that prints the numbers from 1 to 100 to the console. However, if the number is divisible by 3 print `Fizz`. If the number is divisible by 5 print `Buzz`. Finally, if the number is divisible by 3 and 5 print `FizzBuzz`.

Sample Output
```java
1        // 1
2        // 2
Fizz     // 3 is divisible by itself
4        // 4
Buzz     // 5 is divisible by itself
Fizz     // 6 is divisible by 3
7        // 7
8        // 8
Fizz     // 9 is divisible by 3
Buzz     // 10 is divisible by 5
11       // 11
Fizz     // 12 is divisible by 3
13       // 13
14       // 14
FizzBuzz // 15 is divisible by 3 and 5
...      // everything else
98       // 98
Fizz     // 99
Buzz     // 100
```

### #3 Remove Duplicate Characters

Write and consume a method that accepts any string and returns it with no duplicate characters. Both the input and output should be written to the console.

Example
```java
public static void main(){
    final String input = "aabbccdd";
    final String output = removeDuplicates(input);

    System.out.println("Input: " + input);   // input is aabbccdd
    System.out.println("Output: " + output); // output is abcd
}

public static String removeDuplicates(String input) {
    ...
}
```
