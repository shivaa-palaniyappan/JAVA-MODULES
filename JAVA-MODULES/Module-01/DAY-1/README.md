# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
A shop keeper would like to welcome their customers with their name.

Write a java program to get name from the user (String) and print it.

Input Format:

A single line string input.

Output Format:

Hello, [name]

## AIM:
To write a Java program to get the customer name as input and display a welcome message.

## ALGORITHM :
1. Start the program.
2. Import the Scanner class.
3. Create a Scanner object to read input from the user.
4. Read the customer name as a string.
5. Display the message "Hello, " followed by the entered name.
6. Close the scanner.
7. End the program.



## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: PRASANNA I
RegisterNumber: 212223220079
*/
```

## Sourcecode.java:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String name = sc.nextLine();   
        System.out.println("Hello, " + name);
        sc.close();
    }
}
~~~






## OUTPUT:
<img width="462" height="243" alt="image" src="https://github.com/user-attachments/assets/7e36d662-0d6a-4ceb-8d72-916a3f25956f" />



## RESULT:
Thus, the program to read a string from the user and print a greeting message was implemented and verified successfully.
