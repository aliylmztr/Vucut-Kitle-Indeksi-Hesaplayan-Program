# Vucut-Kitle-Indeksi-Hesaplayan-Program
Java Vücut Kitle İndeksi Hesaplayan Program

www.patika.dev

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        double boy, kilo, vucutKitleIndeks;

        Scanner input = new Scanner(System.in);

        System.out.print("Lütfen boyunuzu (metre cinsinde) giriniz : ");
        boy = input.nextDouble();

        System.out.print("Lütfen kilonuzu (kg cinsinde) giriniz : ");
        kilo = input.nextDouble();

        vucutKitleIndeks = kilo / (boy * boy);
        System.out.println("Vücut Kitle İndeksiniz : " + vucutKitleIndeks);
    }
}
