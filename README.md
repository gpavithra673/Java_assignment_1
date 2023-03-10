# Java_assignment_1
## QUESTIONS:
## 1.WRITE A JAVA PROGRAM TOMPRINT THE SUM,MULTIPLY,SUBTRACT AND REMAINDER OF THE TWO NUMBERS.
### CODE: 
![image](https://user-images.githubusercontent.com/93427264/224060226-e9009cf0-3f0e-449f-81f2-61dc113bf536.png)
### OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224060370-4627c454-6b7e-4960-a37f-0f1b746675cb.png)
## 2.WRITE A JAVA PROGRAM TO COMPARE TWO NUMBERS.
### CODE:
![image](https://user-images.githubusercontent.com/93427264/224062176-8779fed5-ca5c-4fb7-89f3-ebc087ce6730.png)
### OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224062319-a2b55f3b-3f88-44eb-a076-e8a0a385699e.png)
## 3.WRITE A JAVA PROGRAM TO CONVERT A STRING TO AN INTEGER.
### CODE:
![image](https://user-images.githubusercontent.com/93427264/224370548-e1cfd0d5-34bd-4a8f-9abc-2fb2467f5807.png)
### OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224370655-7d1835b0-132d-45fa-a435-b1a4f6e39386.png)
## 4.WRITE A JAVA PROGRAM TO FIND AREA OF RHOMBUS
### CODE:
![image](https://user-images.githubusercontent.com/93427264/224369655-8d0d7c71-11f6-45b8-9b30-0b385a8d9335.png)
### OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224369769-34ca521d-06c4-40fa-8697-8b5ea866d1d4.png)
## 5.WRITE A JAVA PROGRAM TO FIND THE NUMBER OF DAYS IN A MONTH.
### CODE: 
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner num= new Scanner(System.in);
        Integer a=num.nextInt();
        switch (a){
            case 1:{
                System.out.print("January");
                break;
            }
            case 2:{
                System.out.print("february");
                break;
            }
            case 3:{
                System.out.print("March");
                break;
            }
            case 4:{
                System.out.print("April");
                break;
            }
            case 5:{
                System.out.print("May");
                break;
            }
            case 6:{
                System.out.print("june");
                break;
            }
            case 7:{
                System.out.print("july");
                break;
            }
            case 8:{
                System.out.print("August");
                break;
            }
            case 9:{
                System.out.print("September");
                break;
            }
            case 10:{
                System.out.print("October");
                break;
            }
            case 11:{
                System.out.print("november");
                break;
            }
            case 12:{
                System.out.print("December");
                break;
            }
            default:{
                System.out.print("Enter number between the given range(1-12)");
                break;
            }
        }
    }
}
~~~
### OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224378132-5b998210-0eab-4758-a200-510f94a89b4c.png)
## 6.WRITE A JAVA CODE TO PRINT THE EVEN NUMBERS FROM 1-20.
### CODE:
![image](https://user-images.githubusercontent.com/93427264/224378712-f1430d81-6434-4764-b90c-10e11add39c3.png)
### OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224378785-e7c5e8d3-241a-4e1b-9bf6-115134480ab4.png)
## 7.WRITE A PROGRAM TO CREATE A SIMPLE CALCULATOR.
### CODE:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        System.out.print("Enter your choice(1-Add,2-Sub,3-Mul,4-Div): ");
        Scanner num= new Scanner(System.in);
        Integer choice=num.nextInt();
        System.out.print("Enter two numbers: ");
        Scanner num1= new Scanner(System.in);
        Integer a=num1.nextInt();
        Scanner num2= new Scanner(System.in);
        Integer b=num2.nextInt();
        switch(choice){
            case 1:{
                int c=a+b;
                System.out.print("Sum: "+c);
                break;
            }
            case 2:{
                int c=a-b;
                System.out.print("Sub: "+c);
                break;
            }
            case 3:{
                int c=a*b;
                System.out.print("Product: "+c);
                break;
            }
            case 4:{
                int c=a/b;
                System.out.print("Divsion: "+c);
                break;
            }
            default:{
                System.out.print("Enter your choice within range(1-4)!!");
                break;
            }
        }
    }
}

~~~
### OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224381174-a3af8da8-aca1-4599-a404-d6b3e9265a20.png)
## 8.WRITE A JAVA PROGRAM TI PRINT MULTIPLICATION TABLE OF GIVEN NUMBER.
### CODE:
![image](https://user-images.githubusercontent.com/93427264/224382268-25fc5f93-9191-4162-b77a-08e4cbb30bf6.png)
### OUTPUT:
![image](https://user-images.githubusercontent.com/93427264/224382333-e5b62762-ca5f-485a-be22-88d24c3f0c10.png)
