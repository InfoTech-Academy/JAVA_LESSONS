# Lesson 6: For loops
## Pre Lesson Reading
https://www.w3schools.com/java/java_for_loop.asp

## W3Schools exercises to complete
https://www.w3schools.com/java/exercise.asp?filename=exercise_while_loop3

## Objective
* Recap of the previous lesson.
* For Loops
* break

## For Loops
* 
```java
for (statement 1; statement 2; statement 3) {
  // code block to be executed
 }
```
* Example of usage
```java
for (int i = 0; i< 10; i++) {
 System.out.println(i);
}
```


## Loops within Loops
* A for loop with a for loop
* Example of usage
```java
for (int i = 0; i< 10; i++) {
  for(int p = 0; p<5; p++) {
    System.out.println(i);
  }
}
```

## Nerdzone

```java
import java.util.Random;
import java.util.Scanner;


public class StarShapes {
    
    public static void main(String[] args) {
      //Exercise 1 : Print out 7 astericks (*)
      //Exercise 2 : Print out the following below:
      // *
      // **
      // ***
      // ****
    }
    
}
```

## Nerdzone ++
* Print out the full christmas tree.
i.e.
```java
  *
 ***
*****
```




