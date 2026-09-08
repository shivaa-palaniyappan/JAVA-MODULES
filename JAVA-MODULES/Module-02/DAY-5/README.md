# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class Calculator with: One non-static method add(int a, int b) that returns the sum, One static method info() that says "Calculator is ready".

## AIM:
To write a Java program to create a Calculator class with a non-static method for addition and a static method to display a message.

## ALGORITHM :
1. Start the program.
2. Create a class named `Calculator`.
3. Create a non-static method `add(int a, int b)` to return the sum of two numbers.
4. Create a static method `info()` to display `"Calculator is ready"`.
5. Create a `Scanner` object to read input.
6. Read two integer values from the user.
7. Call the static method `info()` using the class name.
8. Create an object of the `Calculator` class.
9. Call the `add()` method using the object.
10. Display the sum.
11. End the program.





## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: PRASANNA I
RegisterNumber:  212223220079
*/
```

## SOURCE CODE:
~~~
import java.util.Scanner;

class Calculator {

    int add(int a, int b) {
        return a + b;
    }

    static void info() {
        System.out.println("Calculator is ready");
    }
}

class prog {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int a = sc.nextInt();
        int b = sc.nextInt();

        Calculator.info(); //

        Calculator c = new Calculator();
        int sum = c.add(a, b); 

        System.out.println("Sum: " + sum);
    }
}
~~~






## OUTPUT:
<img width="545" height="308" alt="image" src="https://github.com/user-attachments/assets/242eefc3-0d8f-417c-9634-3868ef4204f9" />



## RESULT:
Thus, the Java program to implement static and non-static methods in a Calculator class was implemented and executed successfully.
