# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java Program to Find the Average of Array Elements.

## AIM:
To write a Java program to find the average of array elements.

## ALGORITHM :
1. Start the program.
2. Import the Scanner class.
3. Create a Scanner object to read input.
4. Read the size of the array n.
5. Create an array of size n.
6. Initialize a variable sum to 0.
7. Use a loop to read array elements and add them to sum.
8. Calculate the average using average = sum / n.
9. Display the average value.
10. Close the scanner.
11. End the program.





## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by:  PRASANNA I
RegisterNumber:  212223220079
*/
```

## SOURCE CODE:
~~~
import java.util.Scanner;
public class AverageOfArray {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();

        int[] arr = new int[n];
        int sum = 0;

        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
            sum += arr[i];
        }

        double average = (double) sum / n;

        System.out.printf("The average of elements is %.2f", average);

        sc.close();
    }
}

~~~






## OUTPUT:
<img width="800" height="487" alt="image" src="https://github.com/user-attachments/assets/4d8056c6-c309-4022-a57e-cc2ef0a5a01f" />



## RESULT:
Thus, the Java program to calculate the average of array elements was implemented and executed successfully.
