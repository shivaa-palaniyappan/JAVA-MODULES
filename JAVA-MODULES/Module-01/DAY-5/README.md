# Ex.No:1(E) STRINGS AND MATH FUNCTION
## QUESTION:
To write a Java program to reverse a given string.
## AIM:
To write a Java program to reverse a given string.

## ALGORITHM :
1. Start the program.
2. Import the `Scanner` class.
3. Create a `Scanner` object to read input.
4. Read the string from the user.
5. Initialize an empty string variable named `reversed`.
6. Use a `for` loop from the last character of the string to the first character.
7. Append each character to the `reversed` string.
8. Display the reversed string.
9. Close the scanner.
10. End the program.
## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by:PRASANNA I
RegisterNumber:  212223220079
*/
```

## SOURCE CODE:
~~~
import java.util.Scanner;

public class ReverseString {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        String str = sc.nextLine();

        String reversed = "";

        for (int i = str.length() - 1; i >= 0; i--) {
            reversed = reversed + str.charAt(i);
        }

        System.out.println("Reversed string: " + reversed);

        sc.close();
    }
}
~~~






## OUTPUT:
<img width="662" height="242" alt="image" src="https://github.com/user-attachments/assets/28d1b219-822c-4be7-937f-9f03c16cbcd8" />



## RESULT:
Thus, the Java program to reverse a given string was implemented and executed successfully.
