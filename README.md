import java.util.Scanner;
public class Main {
        public static void main(String[] args){
                Scanner degistirdim = new Scanner(System.in);
                int mesafe ;
                float perKm = 2.20f, total = 10 ;
                System.out.print("Mesafeyi km cinsinden giriniz :");
                mesafe = degistirdim.nextInt();
                total += mesafe * perKm ;

                total = (total < 20) ? 20 : total ;
                System.out.print("Ödenecek tutar :" + total + " " + "TL");
        }
}
