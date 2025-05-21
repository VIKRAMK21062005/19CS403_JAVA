# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance to calculate the area of circle..

## ALGORITHM :
1.	Start the Program.
2.	Define class `Shapes`:
-	a) Method `print_shape()` to print "Shapes Class"
3.	Define class `Circle` that extends `Shapes`:
-	a) Declare integer `rad`
-	b) Method `get()` to read `rad` from user input
4.	Define class `Area` that extends `Circle`:
-	a) Method `cal()` to calculate `result = 3.14 * rad * rad` and print "Area of Circle is " followed by `result`
5.	In `Main` class `main` method:
-	a) Create `Area` object `obj`
-	b) Call `print_shape()`, `get()`, and `cal()` on `obj` to display shape type, read radius, and calculate area
6.	End


## PROGRAM:
 ```
Program to implement a MultiLevel Inheritance using Java
Developed by: Vikram K
RegisterNumber: 212222040180
```

## Sourcecode.java:
```java
class College
{
    void print_cgeName()
    {
        System.out.println("Saveetha Engineering College");
    }
}
class Department extends College
{
    void print_deptName()
    {
        System.out.println("Computer Science and Engineering");
    }
}
class Student extends Department
{
    void print_stuName()
    {
        System.out.println("John Britto");
    }
}
public class Main
{
    public static void main(String [] args)
    {
        Student st = new Student();
        st.print_cgeName();
        st.print_deptName();
        st.print_stuName();
    }
}
```






## OUTPUT:
 


## RESULT:
Thus the java program for multi-level inheritance was executed successfully.

