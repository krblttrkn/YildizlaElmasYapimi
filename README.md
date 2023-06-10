# ÖDEV :
## YILDIZLARLA ELMAS YAPIMI
* Javada döngüler kullanarak yıldızlarla elmas yapımı
```
import java.util.Scanner;

public class deneme {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.print("Bir Sayı Giriniz : ");
        int n=input.nextInt();

        for (int i=0;i<n;i++){
            System.out.println();
            for (int j=0;j<n-i;j++){
                System.out.print(" ");
            }
            for (int k=0;k<(2*i)+1;k++){
                System.out.print("*");
            }
        }
        for (int i=n-1;i>=0;i--){
            System.out.println();
            for (int j=0;j<(n-i);j++){
                System.out.print(" ");
            }
            for (int k=0;k<(2*i)+1;k++){
                System.out.print("*");
            }
        }

    }
}
```
# PATİKA PROFİLİM
<a href='https://academy.patika.dev/tr/profile'><u>PATİKA PROFİLİM</u></a>