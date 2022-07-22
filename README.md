# java-d-ng-ler-ile-tek-say-girilene-kadar-i-lem-devam-ettirme
Java döngüler ile tek bir sayı girilene kadar kullanıcıdan girişleri kabul eden ve girilen değerlerden çift ve 4'ün katları olan sayıları toplayıp ekrana basan programı yazıyoruz.

    import java.util.Scanner;

    public class Main {

    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        int n, total = 0;

        do {
            System.out.print("Sayı Giriniz :");
            n = inp.nextInt();
            if (n % 2 == 0 && n % 4 == 0) {
                total += n;

            }

        } while (n % 2 == 0);
        System.out.println("Toplam :" + total);

      }
    }
![image](https://user-images.githubusercontent.com/107626332/180398206-0cd3daaa-f192-499a-a9ed-f0af4ec8d920.png)

