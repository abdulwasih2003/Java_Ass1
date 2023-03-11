# Java Assignment-1
## 1. Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.
### Program:
~~~
import java.util.*;
public class Main
{
    public static void main(String[] args) {
        Scanner s=new Scanner(System.in);
        int a=s.nextInt();
        int b=s.nextInt();
        int sum,mul,diff,div,mod;
        sum=a+b;
        diff=a-b;
        mul=a*b;
        div=a/b;
        mod=a%b;
        System.out.println("Sum = "+sum);
        System.out.println("Difference = "+diff);
        System.out.println("Product = "+mul);
        System.out.println("Division = "+div);
        System.out.println("Remainder = "+mod);
    }
}
~~~
### Output:


## 2. Write a Java program to compare two numbers.
### Program:
~~~
import java.util.*;
public class p2 {
    public static void main(String [] args){
        Scanner s= new Scanner(System.in);
        System.out.println("Enter first number :");
        int num1= s.nextInt();
        System.out.println("Enter second number :");
        int num2=s.nextInt();

        if (num1 == num2){
            System.out.println("They are equal");
        }
        else if (num1 > num2) {
            System.out.println(num1+ " is GREATER than " +num2);
        }
        else {
            System.out.println(num2+" is GREATER than "+ num1);
        }
    }
}
~~~
### Output:



## 3. Write a Java program to convert a string to an integer.
### Program:
~~~
import java.util.*;
public class p3{
    public static void main(String [] args){
        Scanner s= new Scanner(System.in);
        System.out.print("Enter a string: ");
        String str= s.next();
        int a=Integer.parseInt(str); ;
        System.out.println("The integer value is "+a);
    }
}
~~~
### Output:



## 4. Java Program to find area of rhombus.
### Program:
~~~
import java.util.*;
public class p4{
    public static void main(String [] args){
        Scanner s= new Scanner(System.in);
        System.out.println("Enter the diagonals of the rhombus :");
        int p= s.nextInt();
        int q= s.nextInt();
        int a=(p*q)/2;
        System.out.println("Area of the Rhombus is "+a);
    }
}
~~~
### Output:



## 5. Write a Java program to find the number of days in a month.
### Program:
~~~
import java.util.Scanner;
public class p5 {
    public static void main(String[] args)
    {
        Scanner s= new Scanner(System.in);
        System.out.print("Enter the month number: ");
        int month = s.nextInt();
        switch (month) {
            case 1:
                System.out.println("January has 31 days.");
                break;
            case 2:
                System.out.println("February has 28 days or 29 days.");
                break;
            case 3:
                System.out.println("March has 31 days.");
                break;
            case 4:
                System.out.println("April has 30 days");
                break;
            case 5:
                System.out.println("May has 31 days");
                break;
            case 6:
                System.out.println("June has 30 days");
                break;
            case 7:
                System.out.println("July has 31 days");
                break;
            case 8:
                System.out.println("August has 31 days");
                break;
            case 9:
                System.out.println("September has 30 days");
                break;
            case 10:
                System.out.println("October has 31 days");
                break;
            case 11:
                System.out.println("November has 30 days");
                break;
            case 12:
                System.out.println("December has 31 days");
                break;
            default:
                System.out.println("Invalid number");
        }

    }
}
~~~
### Output:



## 6. Write a Java program to print the even numbers from 1 to 20.
### Program:
~~~
import java.util.*;
public class p6 {
    public static void main(String [] args){
        int i;
        for(i=1;i<=20;i++) {
            if (i % 2 == 0)
                System.out.print(i + " ");
        }
    }
}
~~~
### Output:



## 7. Write a Java program to create a simple calculator.
### Program:
~~~
import java.util.Scanner;
public class p7 {
    public static void main(String[] args) {
        char op;
        float num1, num2, res;
        Scanner s = new Scanner(System.in);
        System.out.println("Choose an operator: +, -, *, /, or %");
        op = s.next().charAt(0);
        System.out.println("Enter first number");
        num1 = s.nextFloat();
        System.out.println("Enter second number");
        num2 = s.nextFloat();
        switch (op) {

            case '+':
                res= num1 + num2;
                System.out.println(num1 + " + " + num2 + " = " + res);
                break;

            case '-':
                res = num1 - num2;
                System.out.println(num1 + " - " + num2 + " = " + res);
                break;

            case '*':
                res = num1 * num2;
                System.out.println(num1 + " * " + num2 + " = " + res);
                break;

            case '/':
                res = num1 / num2;
                System.out.println(num1 + " / " + num2 + " = " + res);
                break;
            case '%':
                res = num1 % num2;
                System.out.println(num1 + " % " + num2 + " = " + res);
                break;
            default:
                System.out.println("Invalid operator...*");
                break;
        }
    }
}
~~~
### Output:


## 8. Write a Java program to print multiplication table of given number.
### Program:
~~~
import java.util.*;
public class p8 {
    public static void main(String [] args){
        Scanner s=new Scanner(System.in);
        int n=s.nextInt();
        System.out.println("Multiplication table of "+n+":");
        int i;
        for(i=1;i<=10;i++) {

            System.out.println(i+" * "+n+" = "+(i*n));
        }
    }
}
~~~
### Output:



