package com.mycompany.task_5;
import java.util.Scanner;

public class Task_5 {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
              
        System.out.print("Enter the base: ");
        int base = input.nextInt();
        
        System.out.print("Enter the exponent: ");
        int exponent = input.nextInt();
        int result = 1;

        for (int i = 1; i <= exponent; i++) {
            result *= base;
        }
        System.out.println(base + "^" + exponent + " = " + result);
    }
}
