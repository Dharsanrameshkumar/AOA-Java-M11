
# EX 1A Print All Numbers 
## DATE:
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm

1. Start the program.
   
2.Create a Scanner object to read input from the user.

3.Prompt the user to enter an integer N.

4.Use a for loop to iterate from 1 to N.

5.In each iteration, print the current number followed by a space.

6.End the program.

## Program:
```
/*
Program to implement Reverse a String
Developed by: Dharsan R
Register Number: 212223100003
*/

import java.util.Scanner;

public class PrintNumbers {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a number (N): ");
        int N = sc.nextInt();

        for (int i = 1; i <= N; i++) {
            System.out.print(i + " ");
        }

        sc.close();
    }
}
```

## Output:
Enter a number (N): 5  
1 2 3 4 5  



## Result:
The program successfully print all the numbers from 1 to N. 
