# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To write a Java program that takes a number between 1 and 5 from the user and displays the corresponding vowel using switch statement,[a=1,e=2,i=3,o=4,u=5]

## ALGORITHM :
1.Start the program.

2.Import the java.util.Scanner package to read input from the user.

3.Define a class named Demo.

4.In the main method, create a Scanner object named in.

5.Read an integer input from the user and store it in a local variable num.

6.Declare a String variable Name to store the corresponding vowel.

7.Use a switch statement on the value of num.

  a) If num is 1, assign "a" to Name.
  
  b) If num is 2, assign "e" to Name.
 
  c) If num is 3, assign "i" to Name.
  
  d) If num is 4, assign "o" to Name.
  
  e) If num is 5, assign "u" to Name.
  
  f) If num is not in the range 1–5, assign "Invalid range" to Name.

7.Print the value of Name.

8.End the program.

## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: SHREE RAM R
RegisterNumber:  212222040154
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Demo {

    
  public static void main(String[] args)
    {
	   Scanner in = new Scanner(System.in);
       int num = in.nextInt();
       String Name = "";
       switch (num) {
           case 1: Name = "a"; break;
           case 2: Name = "e"; break;
           case 3: Name = "i"; break;
           case 4: Name = "o"; break;
           case 5: Name = "u"; break;
           default:Name = "Invalid range";
       }

      System.out.println(Name);
    }
}

```
## OUTPUT:

![image](https://github.com/user-attachments/assets/ee5e3a12-0243-4554-a007-fa9910c1cc42)

## RESULT:
Thus, the Java program to get a number between 1 and 5 from the user and display the corresponding vowel using a switch statement is successfully created and executed.

