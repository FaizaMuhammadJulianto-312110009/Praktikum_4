package Praktikum_4;
import java.util.Scanner;
public class BangunDatar {
    public void lingkaran()
    {
        Scanner input = new Scanner(System.in);
        double phi = 3.14;
        double r, luas,keliling;
        System.out.println("\n--> lingkaran <--");
        System.out.print("Masukkan Panjang Jari-jari : ");
        r = input.nextDouble();
        System.out.println("=>");
        luas = phi * r * r;
        keliling = 2 * phi * r;
        System.out.print("Luas  = " + (int)luas + " \nKeliling  = "+ (int)keliling);
        System.out.println("");
    }
    public void segitiga()
    {
        Scanner input = new Scanner(System.in);
        double a , t, luas,keliling;
        System.out.println("\n-->Segitiga<--");
        System.out.print("Masukkan Panjang alas : ");
        a = input.nextDouble();
        System.out.print("Masukkan tinggi : ");
        t = input.nextDouble();
        System.out.println("=>");
        luas = 0.5 * a * t;
        keliling = 3 * t;
        System.out.print("Luas  = " + (int)luas + " \nKeliling = "+ (int)keliling);
        System.out.println("");
    }
    public void persegi()
    {
        Scanner input = new Scanner(System.in);
        double s, luas,keliling;
        System.out.println("\n-->Persegi<--");
        System.out.print("Masukkan Panjang sisi : ");
        s = input.nextDouble();
        System.out.println("=>");
        luas = s * s;
        keliling = 4* s;
        System.out.print("Luas  = " + (int)luas + " \nKeliling = "+ (int)keliling);
        System.out.println("");
    }
}
