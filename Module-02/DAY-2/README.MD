# Ex.No:2(B) ACCESS MODIFIERS

## AIM:
To develop a Java Program to display the addition number using private modifiers only.

## ALGORITHM :
1.	Start the program.
2.	Define a class named `addition`
3.	Declare two private integer variables, `num1` and `num2`
4.	Define a private method `add()` that:
a)	Returns the sum of `num1` and `num2`
5.	Define a public method `display(int n1, int n2)` that:
a)	Assigns `n1` to `num1` and `n2` to `num2`
b)	Calls the `add()` method and prints the result using `System.out.println`
6.	Define the `main` method as static
a)	Create an instance of the `addition` class called `ad`
b)	Call the `display(8, 9)` method on the `ad` object
7.	End






## PROGRAM:
 ```
/*
Program to implement a access modifiers using Java
Developed by: SHREE RAM R
RegisterNumber:  212222040154
*/
```

## Sourcecode.java:

```java
class Adder{
    private int num1;
    private int num2;
    Adder(int a, int b)
    {
        this.num1 = a;
        this.num2 = b;
        int result = display();
        System.out.print(result);
    }
    private int display()
    {
        return num1+num2;
    }
    
}
public class Main{
    public static void main(String[] args)
    {
        int num1 = 8, num2 = 9; 
        Adder add = new Adder(num1, num2);
        
    }
}
```

## OUTPUT:

```
Expected    Got 

17          17
```

## RESULT:
Thus the java program to display the addition number using private modifiers only was executed successfully.


