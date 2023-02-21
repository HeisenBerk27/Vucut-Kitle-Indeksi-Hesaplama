# V-cut-Kitle-ndeksi-Hesaplama
www.patika.dev

------------------------------- 


import java.util.Scanner;

public class İndeks {
	
	    public static void main(String[] args) {
	        Scanner scanner = new Scanner(System.in);

	        System.out.print("Lütfen boyunuzu metre cinsinden girin: ");
	        double boy = scanner.nextDouble();

	        System.out.print("Lütfen kilonuzu girin: ");
	        double kilo = scanner.nextDouble();

	        double vucutKitleIndeksi = kilo / (boy * boy);

	        System.out.printf("Vücut Kitle İndeksiniz: %.2f", vucutKitleIndeksi);
	    }
}
