
package bakiye;
import java.util.Scanner;
public class Bakiye {

    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        int sifre,s,secim,miktar,o,islem = 0;        
        boolean cikis= false;
        do {
            System.out.println("Şifre giriniz:");
            s=input.nextInt();
            sifre=1234;
        } while (s!=sifre);
        
        System.out.println("Hoşgeldiniz");
        int bakiye=1000;
        do{
            if (cikis) {
                break;
            }
        do {
            System.out.println("Yapmak istediğiniz işlemi seçiniz:");
            System.out.println("1-Para yükleme");
            System.out.println("2-Para çekme");
            System.out.println("3-Bakiye sorgulama");
            System.out.println("4-Şifre Değiştirme");
            System.out.println("5-Kart iade");
            secim=input.nextInt();
        } while (secim<=0 || secim>5);
        
        
        switch (secim) {
            case 1:
                System.out.println("Yüklemek istediğiniz miktarı giriniz:");
                miktar=input.nextInt();
                bakiye+=miktar;
                System.out.println("Para yatırma işlemi onaylandı.");
                break;
            case 2:
                do {System.out.println("Çekmek istediğiniz miktarı giriniz:");
                miktar=input.nextInt();
                }while(bakiye<miktar);
                bakiye-=miktar;
                System.out.println("Para çekme işlemi onaylandı.");
                break;
            case 3:
                System.out.println("Bakiyeniz: "+bakiye);
                break;
            case 4:
                do {
        
            System.out.println("Yeni şifreyi giriniz:");
            int s1=input.nextInt();
            int s2;

                do {
                    System.out.println("Yeni şifreyi tekrar giriniz:");
                    s2=input.nextInt();
            } while (s1!=s2);
                
            sifre=s1;
            System.out.println("Yeni şifreniz: "+sifre);
            System.out.println("Eğer onaylıyorsanız 1'i,onaylamıyorsanız 2'yi tuşlayınız:");
            o=input.nextInt();
        }
        while(o==2);
        System.out.println("Yeni şifreniz onaylandı.");
                break; 
            case 5 :
                cikis= true;
                break;
            default:
                break;
        }
        do {
        if (secim!=5) {
                System.out.println("Ana menüye dönmek için 8'i tuşlayın:");
                islem=input.nextInt();
        }
        }while(islem!=8);    
        
                    if (cikis) {
                break;
            }
        }while(islem==8);
        
        
        System.out.println("İyi Günler");         
        

    }
    
}
