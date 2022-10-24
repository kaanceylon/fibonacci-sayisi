# fibonacci-sayisi

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int number1 = 0, number2= 1, number3, serial;

        Scanner input = new Scanner(System.in);
        System.out.println("Seri sayısını giriniz : ");
        serial = input.nextInt();

        for (int i =2; i <= serial; i++){
            number3 = number1 + number2;

            System.out.println(number1 + " + " + number2 + " = " + number3);
            number1 = number2;
            number2 = number3;

        }

        System.out.println();



    }
}































