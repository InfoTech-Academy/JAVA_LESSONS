# Lesson 3

Last update: 11 08 2021

## Pre Lesson Reading
- https://www.w3schools.com/java/java_variables.asp
- https://www.w3schools.com/java/java_data_types.asp

## W3Schools exercises to complete
* https://www.w3schools.com/java/exercise.asp?filename=exercise_variables1
* https://www.w3schools.com/java/exercise.asp?filename=exercise_variables2
* https://www.w3schools.com/java/exercise.asp?filename=exercise_variables3
* https://www.w3schools.com/java/exercise.asp?filename=exercise_variables4
* https://www.w3schools.com/java/exercise.asp?filename=exercise_data_types1
* https://www.w3schools.com/java/exercise.asp?filename=exercise_data_types2
* https://www.w3schools.com/java/exercise.asp?filename=exercise_data_types3
* https://www.w3schools.com/java/exercise.asp?filename=exercise_operators1
* https://www.w3schools.com/java/exercise.asp?filename=exercise_operators2
* https://www.w3schools.com/java/exercise.asp?filename=exercise_operators3
* https://www.w3schools.com/java/exercise.asp?filename=exercise_operators4

## Objective
* Recap of the previous lesson.
* Reading: 
* Explain datatypes, use int as an example https://www.w3schools.in/java-tutorial/data-types/
* Get to know the Integer datatype
* Do basic arithmetic 

## The Integer datatype (primitive)
* Explain the differences between a String and an int. i.e. String text has to be surrounded by "" i.e. "5" is not the same as 5.
* An integer is a whole number, without any decimal point.
* Do some basic arithmetic on your integers. 
```java
class HelloWorld {
public static void main(String[] args) {
 int x = 5; 
 int y = 4;
 int ans = x * y;
 System.out.println(ans);
}
```
* Add in a double and do the same operations on a double.
* A double is a whole number with a decimal point.

```java
class HelloWorld {
public static void main(String[] args) {
 double x = 5.0; 
 double y = 4.0;
 double ans = x * y;
 System.out.println(ans);
}
```
## Arithmetic operators

|Operator |Description |
| ------------- | ------------- |
|+ (Addition) |Adds values on either side of the operator.|
|- (Subtraction) |Subtracts right-hand operand from left-hand operand.|	
|* (Multiplication) |Multiplies values on either side of the operator.|
|/ (Division) |Divides left-hand operand by right-hand operand.|
|% (Modulus) |Divides left-hand operand by right-hand operand and returns remainder.|
|++ (Increment) |Increases the value of operand by 1.|
|-- (Decrement) |Decreases the value of operand by 1.|

## Nerdzone


Introduce other data types and print it out

```java
public class MyClass {
  public static void main(String[] args) {
    int myNum = 5;               // integer (whole number)
    double myDoubleNum = 5.0;    // double (decimal number)
    float myFloatNum = 5.99f;    // floating point number
    char myLetter = 'D';         // character
    boolean myBool = true;       // boolean
    String myText = "Hello";     // String    
    System.out.println(myNum);
    System.out.println(myDoubleNum);
    System.out.println(myFloatNum);
    System.out.println(myLetter);
    System.out.println(myBool);
    System.out.println(myText);
  }
}
```
