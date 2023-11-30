#include <stdio.h>

int main() {
    int sayi1, sayi2, carpim;

    printf("İlk sayıyı girin: ");
    scanf("%d", &sayi1);

    printf("İkinci sayıyı girin: ");
    scanf("%d", &sayi2);

    carpim = sayi1 * sayi2;

    printf("Sonuç: %d\n", carpim);

    return 0;
}
