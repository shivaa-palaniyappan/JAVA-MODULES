# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
In mathematics, the factorial of a non-negative integer n, denoted as n!, is the product of all positive integers less than or equal to n. For example:

5! = 5 × 4 × 3 × 2 × 1 = 120

3! = 3 × 2 × 1 = 6

0! is defined as 1.

Write a Java program that prompts the user to enter a non-negative integer and then calculates and displays the factorial of the given number.

Use a for loop to perform the calculation.

Make sure to handle the case when the user enters 0.

Display the result in a clear and user-friendly way.

## AIM:
To write a Java program to find the factorial of a given non-negative integer using a for loop.

## ALGORITHM :
1. Start the program.
2. Import the Scanner class.
3. Create a Scanner object to read input from the user.
4. Read the integer n from the user.
5. Initialize a variable factorial to 1.
6. Use a for loop from 1 to n.
7. Multiply factorial by the loop variable in each iteration.
8. Display the factorial value.
9. Close the scanner.
10. End the program.





## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: PRASANNA I
RegisterNumber:  212223220079
*/
```

## SOURCE CODE:
~~~
import java.util.Scanner;
public class FactorialProgram {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();

        long factorial = 1;  
        for (int i = 1; i <= n; i++) {
            factorial = factorial * i;
        }

        System.out.println("Factorial of " + n + " is: " + factorial);

        sc.close();
    }
}
~~~





## OUTPUT:
<img width="724" height="251" alt="image" src="https://github.com/user-attachments/assets/e4d4c2e6-1b9e-437e-a39d-d106ea73252b" />




## RESULT:
Thus, the Java program to calculate the factorial of a non-negative integer using a for loop was implemented and executed successfully.
