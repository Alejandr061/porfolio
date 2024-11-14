---
title: Programació
layout: default
nav_order: 5
parent: Home
---

# Programació

Aquesta assignatura és en la que més es treballa. De no saber programar res amb `JAVA` a utilitzar bucles (_while, for_) fins a arrays.

Exemple de codi:

```
import java.util.Random;
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int N = scanner.nextInt();
        scanner.nextLine();

        int[] numero = new int[N];
        String[] contenido = new String[N];

        for (int i = 0; i < N; i++) {
            numero[i] = scanner.nextInt();
            contenido[i] = scanner.nextLine();
        }
    }
}
```
