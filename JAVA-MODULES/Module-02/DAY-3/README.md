# Ex.No:2(C) ACCESS SPECIFIERS

## QUESTION:
Write a Java program to create a class called Person with private instance variables name, age. and country. Provide public getter and setter methods to access and modify these variables.
## AIM:
To write a Java program to create a class Person with private instance variables and provide public getter and setter methods to access and modify them.

## ALGORITHM :
1. Start the program.
2. Create a class named `Person`.
3. Declare private variables `name`, `age`, and `country`.
4. Create public getter methods for the variables.
5. Create public setter methods for the variables.
6. Create a `Scanner` object to read input.
7. Create an object of the `Person` class.
8. Read the values for name, age, and country from the user.
9. Use setter methods to store the values in the object.
10. Use getter methods to retrieve the values.
11. Display the person details.
12. End the program.


## PROGRAM:
 ```
/*
Program to implement a Access Specifiers using Java
Developed by: PRASANNA I
RegisterNumber:  212223220079
*/
```

## SOURCE CODE:
~~~
import java.util.Scanner;

class Person {
    private String name;
    private int age;
    private String country;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }

    public String getCountry() {
        return country;
    }

    public void setCountry(String country) {
        this.country = country;
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Person p = new Person();

        p.setName(sc.next());
        p.setAge(sc.nextInt());
        p.setCountry(sc.next());

        System.out.println("Person 1");
        System.out.println("Name: " + p.getName());
        System.out.println("Age: " + p.getAge());
        System.out.println("Country: " + p.getCountry());
    }
}
~~~






## OUTPUT:
<img width="744" height="450" alt="image" src="https://github.com/user-attachments/assets/fca36f50-855b-466d-8553-af3745969b3c" />



## RESULT:
Thus, the Java program to create a Person class with private variables and public getter and setter methods was implemented and executed successfully.
