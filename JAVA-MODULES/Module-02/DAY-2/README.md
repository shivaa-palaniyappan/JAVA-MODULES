# Ex.No:2(B) METHODS

## QUESTION:
Write a method boolean isEven  (int num) without using % operator that returns true if the number is even.

## AIM:
To write a Java method isEven(int num) without using the % operator to check whether a number is even.

## ALGORITHM :
1. Start the program.
2. Create a method named `isEven` with an integer parameter `num`.
3. Use the bitwise AND operator `&` with `1` to check the last bit of the number.
4. If the result is `0`, return `true`.
5. Otherwise, return `false`.
6. Create a `Scanner` object in the `main` method.
7. Read an integer input from the user.
8. Call the `isEven` method with the input number.
9. Display the result.
10. End the program.
	
## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: PRASANNA I
RegisterNumber:  212223220079
*/
```

## SOURCE CODE:
~~~
import java.util.Scanner;

public class NumberUtils {
    public static boolean isEven(int num) {
        return (num & 1) == 0;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        while (!scanner.hasNextInt()) {
            scanner.next();
        }

        int input = scanner.nextInt();
        boolean result = isEven(input);
        System.out.println(result);
    }
}
~~~






## OUTPUT:
<img width="379" height="167" alt="image" src="https://github.com/user-attachments/assets/4d74ca72-c5aa-4d62-9b0f-0e6b7c02ec78" />



## RESULT:
Thus, the Java program to check whether a number is even without using the % operator was implemented and executed successfully.
