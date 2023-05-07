#include <stdio.h>

/*Escreva um programa que leia um número inteiro, maior ou igual a zero, do usuário.
Imprima o enésimo termo da sequência de Fibonacci. Essa sequência começa no termo de
ordem zero, e, a partir do segundo termo, seu valor é dado pela soma dos dois termos
anteriores. Alguns termos dessa sequência são: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34.
*/

int main() {
    int n, primeiro_termo = 0, segundo_termo = 1, proximo_termo, i;

    printf("Digite o valor de n: ");
    scanf("%d", &n);

    // Casos base
    if (n == 0)
        printf("%d\n", primeiro_termo);
    else if (n == 1)
        printf("%d\n", segundo_termo);
    else {
        // Encontra o enésimo termo da sequência de Fibonacci
        for (i = 2; i <= n; i++) {
            proximo_termo = primeiro_termo + segundo_termo;
            primeiro_termo = segundo_termo;
            segundo_termo = proximo_termo;
        }
        printf("%d\n", proximo_termo);
    }

    return 0;
}
