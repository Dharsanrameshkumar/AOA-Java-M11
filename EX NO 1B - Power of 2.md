EX 1B Power of 2
DATE: 19/11/2025
AIM:
To write a Java program to for given constraints.Given an integer n, return true if it is a power of two. Otherwise, return false.

An integer n is a power of two, if there exists an integer x such that n == 2x.

Algorithm
Start the program and import the Scanner class to take input from the user.
Read an integer n using the Scanner object.
Check if n is less than or equal to 0 — if true, return false.
Use the bitwise operation (n & (n - 1)) == 0 to check if n is a power of two.
Print true if the condition holds, otherwise print false.
Program:
/*
Developed by: Dharsan R
Register Number:  212223100003
*/
import java.util.Scanner;

public class Solution {

    public boolean isPowerOfTwo(int n) {
     if (n<=0){
         return false;
     }
     return (n&(n-1))==0;
     
     
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Solution sol = new Solution();
        int n = scanner.nextInt();

        boolean result = sol.isPowerOfTwo(n);
        System.out.println(result);

        scanner.close();
    }
}

Output:
image
Result:
The program successfully implemented and the expected output is verified.
