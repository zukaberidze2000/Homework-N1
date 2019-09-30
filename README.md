package com.company;
import java.util.Scanner;

public class input {
    public static void main(String[] args) {
        Scanner obj = new Scanner(System.in);
        double a, b, c, D;
        System.out.println("enter a, b, c.");

        // input
        a = obj.nextDouble();
        b = obj.nextDouble();
        c = obj.nextDouble();

        // calculation
        D = (b*b)-(4*(a*c)) ;
        double x1 = (b*b) + (4*(a*c));
        double x2 = (b*b) + (4*(a*c));

        System.out.println("x1 = " + x1);
        System.out.println("x2 = " + x2);

    }
}
