#include <stdio.h>

/*Faça um programa que leia 10 inteiros e imprima sua média.*/

int main() {
   int numeros[10];
   int soma = 0;
   float media;
   int i;

   // Lê 10 numeros inteiros do usuário
   for (i = 0; i < 10; i++) {
      printf("Digite o %d numero: ", i+1);
      scanf("%d", &numeros[i]);
   }

   // Calcula a soma dos números
   for (i = 0; i < 10; i++) {
      soma += numeros[i];
   }

   // Calcula a média dos números
   media = (float) soma / 10;

   // Imprime a média dos números
   printf("A media dos numeros informados e: %.2f\n", media);

   return 0;
}
