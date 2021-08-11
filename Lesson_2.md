# Lesson 2

Last Updated: 11 08 2021

## Pre Lesson Reading
- https://www.w3schools.com/java/java_variables.asp
- https://www.w3schools.com/java/java_strings.asp

## W3Schools exercises to complete
* https://www.w3schools.com/java/exercise.asp?filename=exercise_strings1
* https://www.w3schools.com/java/exercise.asp?filename=exercise_strings2
* https://www.w3schools.com/java/exercise.asp?filename=exercise_strings3
* https://www.w3schools.com/java/exercise.asp?filename=exercise_strings4
* https://www.w3schools.com/java/exercise.asp?filename=exercise_strings5
* https://www.w3schools.com/java/exercise.asp?filename=exercise_strings6

## Objective
* Do introductions and take names
* Recap on what was done in the last Lesson
* Introduction to  IDE's and IntelliJ
* Expand on the HelloWorld.java created in Lesson 1
* Introduction to a String variable
* Manipulate a String and output the result

## Introduction to IDE's and IntelliJ
* Create a Project if they haven't done so in the previous lessons.
* Copy the HelloWorld.java into the project and run it within the IDE.
* Do not forget to explain that the IDE is compiling ie. javac and running i.e. java command in the background. 


## String Manipulation

* Explain datatypes and how to create a variable. 
* Introduce Strings

```java
class HelloWorld {
public static void main(String[] args) {
 String hello = "Hello";
 String world = "World";
 System.out.println(hello.concat(world));
}
```

## Resources
https://docs.oracle.com/en/java/javase/13/docs/api/java.base/java/lang/String.html

## Nerd's Zone
* Expand on the main method to get input from a user. Various ways to get input from the user i.e. BufferedReader will work in the iDE, System.in must be run from the console to work. :(
* Assign the input to a String variable.
* Display the number of characters in the console of the String inserted.
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

```java
public class Main {

    public static void main(String[] args) {
        try {
    
            System.out.println("Please enter your name");
            BufferedReader reader =
                    new BufferedReader(new InputStreamReader(System.in));
    
            // Reading data using readLine
            String name = reader.readLine();
    
            // Printing the read line
            System.out.println(name);
        } catch(IOException io) {
        
        }
    
    
    }
}
```
### Alternative

In programming there is always more than one way to skin a cat. The following example does exactly the same as the above, but uses a different class provided by Java to do so.

Thus we can use the `Scanner` class ([Scanner Class Documentation](https://docs.oracle.com/javase/7/docs/api/java/util/Scanner.html)) to read a line from `System.in`
and achieve the same results.

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("Type your name: ");

        String name = scanner.next();
        
        System.out.println(name);
    }
}

```
## Homework

* Also ask for the last name and print it out.

> 
