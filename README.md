# Hava-Sicakligina-Gore-Etkinlik-Ogrenme
---
Bu bir [patika.dev](www.patika.dev) projesidir.
```
import java.util.Scanner;
public class havaDurumu {
    public static void main(String[] args) {
        int heat;
        Scanner input = new Scanner (System.in);
        System.out.print("Sıcaklık Derecesini Giriniz: ");
        heat = input.nextInt();

        if (heat < 5){
            System.out.print("Kayağa Gidebilirsiniz");
        }else if (heat >=5 && heat <15){
            System.out.print("Sinemaya Gidebilirsiniz");
        } else if (heat >=15 && heat <= 25){
            System.out.print("Pikniğe Gidebilirsiniz");
        } else {
            System.out.print("Yüzmeye Gidebilirsiniz");
        }
    }
}
```
