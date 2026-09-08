# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
A pirate ship has a code lock that only opens if:

The input code is even, and

If it is less than 100, say "Weak Code".

If it is between 100 and 999, say "Strong Code".

If the code is odd, deny access -"Access Denied".

For example:

Input	Result
42
Weak Code

## AIM:
To write a Java program to check whether the given pirate code is valid and display the appropriate message based on the conditions.

## ALGORITHM :
1. Start the program.
2. Import the Scanner class.
3. Create a Scanner object to read input.
4. Read the code number from the user.
5. Check whether the code is even.
6. If the code is even and less than 100, print "Weak Code".
7. Else if the code is even and between 100 and 999, print "Strong Code".
8. Otherwise, print "Access Denied".
9. Close the scanner.
10. End the program.





## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by:  PRASANNA I
RegisterNumber:  212223220079
*/
```

## SOURCE CODE:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int code = sc.nextInt();

        if (code % 2 == 0) {
            if (code < 100) {
                System.out.println("Weak Code");
            } else if (code <= 999) {
                System.out.println("Strong Code");
            } else {
                System.out.println("Access Denied");
            }
        } else {
            System.out.println("Access Denied");
        }

        sc.close();
    }
}
~~~






## OUTPUT:
<img width="460" height="297" alt="image" src="https://github.com/user-attachments/assets/8c783cca-d5aa-4a09-81a0-53eaa61ee349" />



## RESULT:
Thus, the Java program to validate the pirate ship code and display the corresponding message was implemented and executed successfully.
