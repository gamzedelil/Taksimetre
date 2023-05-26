# Taksimetre
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        int km;
        double perkm = 2.20;
        double tutar = 10; 
        
        Scanner input = new Scanner(System.in);
        System.out.print("Mesafe kac km:");
        km = input.nextInt();
    
        tutar += (km * perkm);
        tutar = ( tutar < 20) ? 20 : tutar;
        System.out.println("Odenecek tutar:" +tutar);
        
        
    }
}
