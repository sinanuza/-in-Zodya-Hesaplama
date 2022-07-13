# -in-Zodya-Hesaplama
www.patika.dev Çin Zodyağı Hesaplama




        import java.util.Scanner;
        public class Cin_Zodaygi {
        public static void main(String[] args) {
        int yil;
        String zodyagı="";
        System.out.println("Lutfen dogum yilinizi giriniz:");
        Scanner input=new Scanner(System.in);
        yil=input.nextInt();
        yil=yil%12;
        switch (yil){
            case 0:
                zodyagı="Maymun";
                break;
            case 1:
                zodyagı="Horoz";
                break;
            case 2:
                zodyagı="Kopek";
                break;
            case 3:
                zodyagı="Domuz";
                break;
            case 4:
                zodyagı="Fare";
                break;
            case 5:
                zodyagı="Okuz";
                break;
            case 6:
                zodyagı="Kaplan";
                break;
            case 7:
                zodyagı="Tavsan";
                break;
            case 8:
                zodyagı="Ejderha";
                break;
            case 9:
                zodyagı="Yilan";
                break;
            case 10:
                zodyagı="At";
                break;
            case 11:
                zodyagı="Koyun";
                break;
            default: System.out.println("Hatali bir secim yaptiniz!");
        }
        System.out.println("Cin Zodyagini Burcunuz:"+zodyagı);
    }
}
