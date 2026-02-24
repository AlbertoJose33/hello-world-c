# hello-world-c
#include <stdio.h>
int main() {
    printf("Hello, World!\n");
    return 0;
}
primeiro programa em C, inicio da minha jornada em engenharia da computaçäo.

24.02.2026
número do meio:
#include <stdio.h>
#include <math.h>
int main() {
	int numero;
	printf("Digite um numero de 3 digitos:");
	scanf("%d", &numero);
	int digito;
	digito = (numero/10)%10;
	printf("Dezena: %d", digito);
	return 0;
	
}
