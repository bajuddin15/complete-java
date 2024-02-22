# complete-java-fullstack

## Roadmap -
1. [Java Basics](#java-basics)
2. OOPs
3. Collection Framwork
4. Data Structures & Algorithms
5. Spring Boot
6. Additional Tools

### 1. <a name="java-basics">Java Basics</a> -
1. Variable & Data Types
2. Conditional Statement
3. Loops
4. Arrays & Strings
5. Exception Handling


#### 1. Variable & Data Types -
- Data types specify the different sizes and values that can be stored in the variable. There are two types of data types in Java:

**1. Primitive data types:** The primitive data types include boolean, char, byte, short, int, long, float and double.

**2. Non-primitive data types:** The non-primitive data types include Classes, Interfaces, and Arrays.

#### Primitive Data Types:-
In Java language, primitive data types are the building blocks of data manipulation.

> Java is a statically-typed programming language. It means, all [variables](https://www.javatpoint.com/java-variables) must be declared before its use. That is why we need to declare variable's type and name.

eg:- boolean, byte, short, int, long, float, double

#### Non  Primitive :-
eg:- String, Array

### Java Control Statement:-
Java provides three types of control flow statements.

1.  **Decision Making statements**
    -   if statements
    -   switch statement
1.  **Loop statements**
    -   do while loop
    -   while loop
    -   for loop
    -   for-each loop
2.  **Jump statements**
    -   break statement
    -   continue statement
 
 1. **If else :-** You already know so see only example:-
 ```java
 public  class  IfElseIfExample {
     public  static  void  main(String[] args) {
         int  number  =  10;
         if (number > 0) {
             System.out.println("The number is positive.");
         } else  if (number < 0) { 
             System.out.println("The number is negative."); 
         } else { 
             System.out.println("The number is zero.");
         } 
     } 
 }
  ```

2. **Switch Statement**:-

```java
public class SwitchExample {
    public static void main(String[] args) {
        int day = 3;
        String dayName;
        switch (day) {
            case 1:
                dayName = "Monday";
                break;
            case 2:
                dayName = "Tuesday";
                break;
            case 3:
                dayName = "Wednesday";
                break;
            case 4:
                dayName = "Thursday";
                break;
            case 5:
                dayName = "Friday";
                break;
            case 6:
                dayName = "Saturday";
                break;
            case 7:
                dayName = "Sunday";
                break;
            default:
                dayName = "Invalid day";
                break;
        }
        System.out.println("The day is " + dayName);
    }
}
```



## Loops in Java

Loops in Java are control structures that allow you to execute a block of code repeatedly based on a condition. There are three main types of loops in Java: `for`, `while`, and `do-while`.

### 1. For Loop:
The `for` loop is used when you know how many times you want to execute a block of code.

```java
for (initialization; condition; iteration) {
    // code to be executed
}
```

- `initialization`: Initialize the loop control variable.
- `condition`: Defines the condition for executing the loop.
- `iteration`: Updates the loop control variable after each iteration.

**Example:**

```java
for (int i = 0; i < 5; i++) {
    System.out.println("Iteration " + (i + 1));
}
```

### 2. While Loop:
The `while` loop repeats a block of code while a specified condition is true.

```java
while (condition) {
    // code to be executed
}
```

**Example:**

```java
int i = 0;
while (i < 5) {
    System.out.println("Iteration " + (i + 1));
    i++;
}
```

### 3. Do-While Loop:
The `do-while` loop is similar to the `while` loop, but it guarantees that the block of code is executed at least once before the condition is checked.

```java
do {
    // code to be executed
} while (condition);
```

**Example:**

```java
int i = 0;
do {
    System.out.println("Iteration " + (i + 1));
    i++;
} while (i < 5);
```

### Jump Statements in Java

Jump statements in Java are used to alter the flow of control in a program. They allow you to transfer control to another part of the program. Java supports two types of jump statements:

1. **Break Statement:** The `break` statement is used to terminate the loop or switch statement and transfer control to the statement immediately following the loop or switch.

2. **Continue Statement:** The `continue` statement is used to skip the remaining code inside a loop for the current iteration and continue with the next iteration.

 
