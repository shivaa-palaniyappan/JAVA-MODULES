# Ex.No:3(F) WRAPPER CLASS

## QUESTION:

Write a Java program to find the square root of a number using the Double Wrapper Class.
<img width="395" height="162" alt="image" src="https://github.com/user-attachments/assets/6214cc44-7c45-4cfb-a080-bcea31ff8e2f" />

## AIM:

To write a Java program that finds the square root of a given number using the Double Wrapper Class.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a Scanner object to read input from the user.
4. Read a number and store it in a Double wrapper object.
5. Use the Math.sqrt() method to calculate the square root.
6. Display the square root of the given number.
7. Close the scanner.
8. Stop the program.





## PROGRAM:
 ```
/*
Program to implement a Wrapper Class using Java
Developed by:PRASANNA I
RegisterNumber: 212223220079
*/
```

## SOURCE CODE:

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        if (scanner.hasNextDouble()) {
            Double number = scanner.nextDouble(); // Double Wrapper Class

            Double squareRoot = Math.sqrt(number);

            System.out.println("Square root of " + number + " is: " + squareRoot);
        }

        scanner.close();
    }
}





## OUTPUT:

<img width="878" height="269" alt="image" src="https://github.com/user-attachments/assets/76c3f728-5b2b-4c4c-aefd-7fd617e6da16" />



## RESULT:

Thus, the Java program to find the square root of a number using the Double Wrapper Class was implemented and executed successfully.
