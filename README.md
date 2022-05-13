# Manav-Kasa-Programi

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

        double armut=2.14, elma=3.67,domates=1.11,muz=0.95,patlican=5,tutar;
        int kilo;
        tutar=0;

        Scanner input = new Scanner(System.in);

        System.out.println("Armut Kaç Kilo? ");
        kilo = input.nextInt();
        tutar = tutar + kilo*armut;
        System.out.println("Elma Kaç Kilo? ");
        kilo = input.nextInt();
        tutar = tutar + kilo*elma;
        System.out.println("Domates Kaç Kilo? ");
        kilo = input.nextInt();
        tutar = tutar + kilo*domates;
        System.out.println("Muz Kaç Kilo? ");
        kilo = input.nextInt();
        tutar = tutar + kilo*muz;
        System.out.println("Patlıcan Kaç Kilo? ");
        kilo = input.nextInt();
        tutar = tutar + kilo*patlican;

        System.out.println("Ödeyeceğiniz Toplam tutar :" + tutar);

    }
}
