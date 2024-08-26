# att01 Matheus Rocha de Souza 

Hello, Word! #include <stdio.h> int main(){ printf("hello, Word!\n"); } 
2- soma de dois numeros #include <stdio.h>

int main (){ int num1; int num2; int soma;

printf("digite um numero:"); scanf("%d", &num1); printf("digite outro numero:"); scanf("%d", &num2);

soma = num1 + num2; printf("A soma de %d e %d é %d\n", num1, num2, soma);

return 0; } 
3- impar ou par #include <stdio.h>

int main (){ int numero; int par, impar;

printf("digite um numero:"); scanf("%d", &numero);

if (numero % 2 == 0) { printf("O número %d é par.\n", numero); } else { printf("O número %d é ímpar.\n", numero); } } 
4- Maior de Dois Números #include <stdio.h>

int main (){ int numero1; int numero2;

printf("digite um numero:"); scanf("%d", &numero1); printf("digite outro numero:"); scanf("%d", &numero2);

if (numero1 > numero2) { printf("O número %d e maior\n", numero1); } else { printf("O número %d é maior\n", numero2); } }  
5- cacular a media

#include <stdio.h>

int main() { int num1, num2, num3; float media;

printf("Digite o primeiro número: "); scanf("%d", &num1);

printf("Digite o segundo número: "); scanf("%d", &num2);

printf("Digite o terceiro número: "); scanf("%d", &num3);

media = (num1 + num2 + num3) / 3.0;

printf("A média aritmética dos números %d, %d e %d é %.2f\n", num1, num2, num3, media);

return 0; }
6- Cálculo da Área de um Círculo #include<stdio.h>

int main(){

float base; float altura;

printf("escreva o valor da altura do circulo:"); scanf("%f", &altura); printf("escreva a qual o valor base do circulo:"); scanf("%f", &base);

float total = base * altura;

printf("o calculo da area do circulo e:, %.2f\m", total);

return 0;

} 7- conversão de temperatura #include<stdio.h>

int main () { float Fahrenheit; float celsius; float total;

printf("digite um valor para Fahrenheit:"); scanf("%f", &Fahrenheit);

total = (Fahrenheit-32)/1.8;

printf("o valor em celsius e: %f", total);

return 0; } 
8- tabuada #include <stdio.h>

int main() { int numero, i;

printf("Digite um número para ver a tabuada: "); scanf("%d", &numero);

printf("Tabuada de %d:\n", numero); for(i = 1; i <= 10; i++) { printf("%d x %d = %d\n", numero, i, numero * i);

} return 0; }
9- fatorial de um numero #include <stdio.h>

int main() { int numero, i; unsigned long long fatorial = 1;

printf("Digite um número inteiro positivo: "); scanf("%d", &numero);

if (numero < 0) { printf("Fatorial não é definido para números negativos.\n"); } else {

for (i = 1; i <= numero; i++) {
    fatorial *= i;
}

printf("Fatorial de %d = %llu\n", numero, fatorial);
}

return 0; } 
10- contagem regressiva #include <stdio.h>

int main() { int i;

printf("Contagem regressiva:\n"); for (i = 10; i >= 1; i--) { printf("%d\n", i); }

printf("Feliz Ano Novo!\n");

return 0; }
