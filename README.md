### Burç Hesaplama:

> **Koç Burcu :** 21 Mart - 20 Nisan
> **Boğa Burcu :** 21 Nisan - 21 Mayıs
> **İkizler Burcu :** 22 Mayıs - 22 Haziran
> **Yengeç Burcu :** 23 Haziran - 22 Temmuz
> **Aslan Burcu :** 23 Temmuz - 22 Ağustos
> **Başak Burcu :** 23 Ağustos - 22 Eylül
> **Terazi Burcu :** 23 Eylül - 22 Ekim
> **Akrep Burcu :** 23 Ekim - 21 Kasım
> **Yay Burcu :** 22 Kasım - 21 Aralık
> **Oğlak Burcu :** 22 Aralık - 21 Ocak
> **Kova Burcu :** 22 Ocak - 19 Şubat
> **Balık Burcu :** 20 Şubat - 20 Mart

```java
import java.util.Scanner;

public class Solution {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int gün, ay;

        System.out.println("Doğduğunuz Ayı Giriniz");
        ay = input.nextInt();

        System.out.println("Doğduğunuz Günü Giriniz");
        gün = input.nextInt();

        if (ay == 1) {
            if (gün < 22)
                System.out.println("Oğlak");
            else
                System.out.println("Kova");
        }
        else if (ay == 2) {
            if (gün < 20)
                System.out.println("Kova");
            else
                System.out.println("Balık");
        }
        else if (ay == 3) {
            if (gün < 21)
                System.out.println("Balık");
            else
                System.out.println("Koç");
        }
        else if (ay == 4) {
            if (gün < 21)
                System.out.println("Koç");
            else
                System.out.println("Boğa");
        }
        else if (ay == 5) {
            if (gün < 22)
                System.out.println("Boğa");
            else
                System.out.println("İkizler");
        }
        else if (ay == 6) {
            if (gün < 23)
                System.out.println("İkizler");
            else
                System.out.println("Yengeç");
        }
        else if (ay == 7) {
            if (gün < 23)
                System.out.println("Yengeç");
            else
                System.out.println("Aslan");
        }
        else if (ay == 8) {
            if (gün < 23)
                System.out.println("Aslan");
            else
                System.out.println("Başak");
        }
        else if (ay == 9) {
            if (gün < 23)
                System.out.println("Başak");
            else
                System.out.println("Terazi");
        }
        else if (ay == 10) {
            if (gün < 23)
                System.out.println("Terazi");
            else
                System.out.println("Akrep");
        }
        else if (ay == 11) {
            if (gün < 23)
                System.out.println("Akrep");
            else
                System.out.println("Yay");
        }
        else if (ay == 12) {
            if (gün < 23)
                System.out.println("Yay");
            else
                System.out.println("Oğlak");
        }

    }
}
```

