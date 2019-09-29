package com.company;

public class gantoleba {
    public static void main(String []args)
    {
        double a = 1.1f;
        double b = 2.2f;
        double c = 3.3f;
        double D;
        D = (b*b)-(4*(a*c)) ;
        if (D < 0)
            System.out.println("does not have answer");
        else {
            if (D == 0) {
                System.out.println("has two answer");
            } else {
                System.out.println("has one answer");
            }

        }
    }
}
