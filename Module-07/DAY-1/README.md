# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To Develop a Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism.

## ALGORITHM :
1.  Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `Example1`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read integers `a` and `b` from user input
-	b) Calculate `res = a / b` and print "Result: " followed by `res`
5.	Use `catch` block to handle `ArithmeticException`:
-	a) If division by zero occurs, print "You Shouldn't divide a number by zero"
6.	End


## PROGRAM:
 ```
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: Vikram K
RegisterNumber: 212222040180
```

## Sourcecode.java:
```java
import java.util.Scanner;

public class HelloWorld {
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
           try
           {
               int a=sc.nextInt();
             int b=sc.nextInt();
             int c=a/b;
             System.out.println("Result: " +c); 
           }
               catch(ArithmeticException e)  
        {  
            System.out.println("Arithmetic Exception: Number should not divide by zero");  
        }  
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/f3314517-1090-4bc4-8cc0-acfef0439ffd)


## RESULT:
Thus the Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism was executed successfully.

