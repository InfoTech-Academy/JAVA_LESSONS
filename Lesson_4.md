# Lesson 4
## Pre Lesson Reading
* https://www.w3schools.com/java/java_booleans.asp
* https://www.w3schools.com/java/java_conditions.asp

## W3Schools exercises to complete
* https://www.w3schools.com/java/exercise.asp?filename=exercise_booleans1
* https://www.w3schools.com/java/exercise.asp?filename=exercise_booleans2
* https://www.w3schools.com/java/exercise.asp?filename=exercise_conditions1
* https://www.w3schools.com/java/exercise.asp?filename=exercise_conditions2
* https://www.w3schools.com/java/exercise.asp?filename=exercise_conditions3
* https://www.w3schools.com/java/exercise.asp?filename=exercise_conditions4
* https://www.w3schools.com/java/exercise.asp?filename=exercise_conditions5

## Objective
* Recap of the previous lesson.
* Intro/Recap of booleans
* Logical operators
* Java Conditions and If statements

## W3 Schools
* We following the W3 Schools syllabus online. https://www.w3schools.com/java/default.asp 

## Booleans again
* 
```java
class HelloWorld {
public static void main(String[] args) {
 boolean a = true;
 boolean b = false;
}
```
* Add in a double and do the same operations on a double.
* A double is a whole number with a decimal point.

### Logical Operators

|Operator |Description |
| ------------- | ------------- |
|> |More than|
|>= |More than or Equal|
|< |Less than|	
|<= |Less than or Equal|	
|== |Equals|
|!= |Not Equal|

* Expand on you main method, now try to add in a condition using the logical operators, ==, >, <, >== etc and see the console output

```java
class HelloWorld {
public static void main(String[] args) {
 int x = 5;
 int y = 9;
 System.out.println(x==y);
}
```

## If statements
* If ... else
* Reference https://www.w3schools.com/java/java_conditions.asp 

```java
class HelloWorld {
public static void main(String[] args) {
 int x = 5;
 int y = 9;
 if (x < y) {
   System.out.println("x is less than y");
 } else {
   System.out.println("x is more than y");
 }
}
```

## Nerdzone

```java
import java.util.Random;
import java.util.Scanner;


public class HelloWorldContinued {
    
    public static void main(String[] args) {
    
        // Generate a random number
        Random randomGenerator = new Random();
        int guessInt = randomGenerator.nextInt(10) + 1;
    
        // Guess the number
        Scanner scanner = new Scanner(System.in);
    
        System.out.println("What is the number: ");
    
        int answer = scanner.nextInt();
        
        /* Exercise: add in the if statements and print out one of the following:
           - WRONG your guess was too high. If the answer value was more then the generated number.
           - CORRECT. If the answer matched the generated value.
           - WRONG your guess was too low. If the answer value was less then the generated number.
        */
    
    }
    
}
```





