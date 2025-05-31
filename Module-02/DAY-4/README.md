# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that returns the sum of all the values in a 2D array.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: SHREE RAM R
RegisterNumber:  212222040154
*/
```

## Sourcecode.java:

```java
import java.util.*;
public class Main{
    public static void main(String[] args)
    {
        int[][] arr = {{1,2,3,4,5},{2,4,6,8,10},{1,3,5,7,9}};
        int sum = 0;
        for(int row = 0 ; row< arr.length;row++)
        {
            for(int col = 0; col < arr[row].length; col++)
            {
                sum += arr[row][col];
            }
        }
        System.out.print("Sum of all elements is: " + sum);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/1617df36-e87d-40a9-95ea-5bb95a28f355)


## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.


