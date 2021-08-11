# Lesson 5 : Switch-case, while and do-while loops
## Pre Lesson Reading
https://www.w3schools.com/java/java_switch.asp
https://www.w3schools.com/java/java_while_loop.asp

## W3Schools exercises to complete
* https://www.w3schools.com/java/exercise.asp?filename=exercise_switch1
* https://www.w3schools.com/java/exercise.asp?filename=exercise_switch2
* https://www.w3schools.com/java/exercise.asp?filename=exercise_while_loop1
* https://www.w3schools.com/java/exercise.asp?filename=exercise_while_loop2

## Objective
* Recap of the previous lesson.
* Switch-case statement
* While loops
* do...while loops

## Switch Statements
* 
```java
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
```
* Example of usage
```java
class SwitchTest {
public static void main(String[] args) {
 switch (day) {
  case 1:
    System.out.println("Monday");
    break;
  case 2:
    System.out.println("Tuesday");
    break;
  case 3:
    System.out.println("Wednesday");
    break;
  case 4:
    System.out.println("Thursday");
    break;
  case 5:
    System.out.println("Friday");
    break;
  case 6:
    System.out.println("Saturday");
    break;
  case 7:
    System.out.println("Sunday");
    break;
}
```
## While Loops
```java
while(condition is true) {
 //do something
 // make sure that the condition will become true otherwise, you will loop infinitely.
}
```

* Example
```java
int i = 0;
while (i < 5) {
 System.out.println(i);
 i++; //increment i, otherwise you'll never meet the condition 
      //and loop forever.....and ever
}
```

## Do-while Loops
```java
do {
 //do something, while a certain condition is true
 //Once again make sure the condition will be met at a point, 
 //other you'll loop infinitely
} while(condition is true)
```
* Example

```java
int i = 0;
do {
 System.out.println(i);
 i++; //increment i, otherwise you'll never meet the condition 
      //and loop forever.....and ever
} while (i < 5)
```
* What do you notice is the difference between a while and do-while loop?

## Nerdzone

```java
import java.util.Random;
import java.util.Scanner;


public class GuessUntilYouBlue {
    
    public static void main(String[] args) {
    
        // Generate a random number between 1 and 10
        Random randomGenerator = new Random();
        int guessInt = randomGenerator.nextInt(10) + 1;
    
        /**** Exercise, loop until the user guesses the right answer! ***/
        
        // Guess the number
        Scanner scanner = new Scanner(System.in);
    
        System.out.println("What is the number: ");
        int answer = scanner.nextInt();
        
    }
    
}
```

## Nerdzone ++ 
* Adjust the code above, add in an if statement that you learnt in lesson 4 to give the user hints i.e.

```java
if (number is greater that the generated) {
 //Guess lower
} else {
 // Guess higher
}
```



