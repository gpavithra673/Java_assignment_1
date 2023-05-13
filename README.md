# BASIC ARITHMETIC OPERATIONS(JAVA)
## AIM: 
### WRITE A JAVA PROGRAM TO PRINT THE ARITHMETIC OPERATIONS
## PROCEDURE:
### 1.Create the main class and declare the main method so that the program can be identified and start running.
### 2.In main method decalre two variables with appropriate data type declaration.
### 3.Perform the basic arithmatic operations (addition,subtraction,multiplication,division).
### 4.Print the output using "System.outprintln" to see the results.
### 5.The program completes it's execution and the output will be displayed eventually.
## CODE: 
```
import java.util.Scanner;
public class math_calc
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter first number: ");
        int a = sc.nextInt();
        System.out.print("Enter second number: ");
        int b = sc.nextInt();
        System.out.println("Addition = "+(a+b));
        System.out.println("Subtraction = "+(a-b));
        System.out.println("Multiply = "+(a*b));
        System.out.println("Divide = "+(a/b));
        System.out.println("Reminder = "+(a%b));
    }
}
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224060370-4627c454-6b7e-4960-a37f-0f1b746675cb.png)
## RESULT: 
### Thus the code for arithmetic operation in java is executed successfully and obatined the results.
