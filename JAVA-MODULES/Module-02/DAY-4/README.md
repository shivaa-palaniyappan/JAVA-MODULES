# Ex.No:2(D) VARIABLE SCOPE AND CONSTRUCTOR

## QUESTION:
Implement a class Employee with a parameterized constructor to initialize id, name, and salary.

## AIM:
To write a Java program to implement a class Employee with a parameterized constructor to initialize employee details.

## ALGORITHM :
1. Start the program.
2. Create a class named `Employee`.
3. Declare the variables `id`, `name`, and `salary`.
4. Create a parameterized constructor to initialize the variables.
5. Create a method to display employee details.
6. Create a `Scanner` object to read input.
7. Read employee id, name, and salary from the user.
8. Create an object of the `Employee` class using the parameterized constructor.
9. Call the display method to show employee details.
10. Close the scanner.
11. End the program.
	





## PROGRAM:
 ```
/*
Program to implement a Variable scope and Constructor using Java
Developed by: PRASANNA I
RegisterNumber:  212223220079
*/
```

## SOURCE CODE:
~~~
import java.util.Scanner;

class Employee {
    int id;
    String name;
    double salary;
    
    Employee(int id, String name, double salary) {
        this.id = id;
        this.name = name;
        this.salary = salary;
    }
    void display() {
        System.out.println("Employee Details:");
        System.out.println("Employee ID: " + id);
        System.out.println("Employee Name: " + name);
        System.out.println("Employee Salary: " + salary);
    }
}

public class prog {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int id = sc.nextInt();
        sc.nextLine(); 
        String name = sc.nextLine();
        double salary = sc.nextDouble();
        Employee emp = new Employee(id, name, salary);

        emp.display();

        sc.close();
    }
}
~~~






## OUTPUT:
<img width="669" height="457" alt="image" src="https://github.com/user-attachments/assets/fac03839-c9ed-4a81-8cb4-13d97aceaab1" />




## RESULT:
Thus, the Java program to implement an Employee class using a parameterized constructor was implemented and executed successfully.
