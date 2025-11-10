
# EX 1B Power of 2
## DATE:
## AIM:
To write a Java program to for given constraints.Given an integer n, return true if it is a power of two. Otherwise, return false.

An integer n is a power of two, if there exists an integer x such that n == 2x.

## Algorithm
1.Start the program.

2.Create a Scanner object to read input from the user.

3.Read an integer n from the user.

4.If n is less than or equal to 0, it is not a power of two.

5.Use a loop or bitwise operation to check if n is a power of two.

6.Using bitwise: A number n is a power of two if (n & (n - 1)) == 0.

7.Display whether the number is a power of two or not.

8.End the program. 

## Program:
```
/*
Program to implement Reverse a String
Developed by: Dharsan R
Register Number: 212223100003 
*/

import java.util.Scanner;

public class PowerOfTwo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int n = sc.nextInt();

        boolean isPowerOfTwo = false;

        if (n > 0 && (n & (n - 1)) == 0) {
            isPowerOfTwo = true;
        }

        if (isPowerOfTwo)
            System.out.println(n + " is a power of 2.");
        else
            System.out.println(n + " is not a power of 2.");

        sc.close();
    }
}
```

## Output:
Enter a number: 8  
8 is a power of 2.



## Result:
The program successfully implemented and the expected output is verified.
