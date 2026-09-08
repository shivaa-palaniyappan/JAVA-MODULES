# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Course with attributes code, title, credits.
## AIM:
To create a Java class Course with attributes code, title, and credits, and display the course details.
## ALGORITHM :
1. Start the program.
2. Import the `Scanner` class.
3. Create a class named `Course`.
4. Declare the attributes `code`, `title`, and `credits` in the `Course` class.
5. Create a `Scanner` object to read input.
6. Create the first `Course` object.
7. Read and store the code, title, and credits for the first course.
8. Create the second `Course` object.
9. Read and store the code, title, and credits for the second course.
10. Display the details of both courses.
11. Close the scanner.
12. End the program.
	
 ## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by:PRASANNA I 
RegisterNumber:  212223220079
*/
```

## SOURCE CODE:
~~~
import java.util.Scanner;

class Course {
    String code;
    String title;
    int credits;
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Course c1 = new Course();
        c1.code = sc.next();
        c1.title = sc.next();
        c1.credits = sc.nextInt();

        Course c2 = new Course();
        c2.code = sc.next();
        c2.title = sc.next();
        c2.credits = sc.nextInt();

        System.out.println(c1.code + " | " + c1.title + " | " + c1.credits + " credits");
        System.out.println(c2.code + " | " + c2.title + " | " + c2.credits + " credits");

        sc.close();
    }
}
~~~






## OUTPUT:
<img width="815" height="249" alt="image" src="https://github.com/user-attachments/assets/20ccbadf-14cd-4995-bb4b-5f7c9fc819e0" />



## RESULT:
Thus, the Java program to create a Course class and display course details was implemented and executed successfully.
