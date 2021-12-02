```java
import java.util.Scanner;
public class main {
    public static void main(String[] args) {

        double birinciKenar, ikinciKenar,ucuncuKenar;

        Scanner input = new Scanner(System.in);

        System.out.print("1. Kenarı Girin: ");
        birinciKenar = input.nextDouble();

        System.out.print("2. Kenarı Girin: ");
        ikinciKenar = input.nextDouble();
        ucuncuKenar=sqrt((birinciKenar*birinciKenar)+(ikinciKenar*ikinciKenar));
           

        System.out.print("ucuncu kenar: "+ucuncuKenar);


    }
}

```
