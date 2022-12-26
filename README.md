# daire
package day01;

import java.util.Scanner;

public class day6 {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.print("Dairenin yarıçap değerini giriniz= ");
        int r = scan.nextInt();
        double alan = Math.PI * r * r;
        double cevre = 2* Math.PI *r;

        System.out.println("Dairenin Alanı = " + alan);
        System.out.println("Dairenin Çevresi = " + cevre);
        
    }
}
