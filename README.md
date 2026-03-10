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




#include <stdio.h>
int main (){
	int proteina, sobremesa, bebida;
	int total = 0;
	int calprato;
	printf("Escolha um prato: \n");
	printf("1-vegetariano(180cal)\n");
	printf("2-peixe(230cal)\n");
    printf("3-frango(250cal)\n ");
    printf("4-carne(350cal)\n");
    scanf("%d", &proteina); 
    int calsobremesa;
    printf("Escolha uma sobremesa: \n");
    printf("1-abacaxi(75cal)\n");
    printf("2-sorvete diet(110cal)\n");
    printf("3-mousse diet(170cal)\n");
    printf("4-mousse chocolate\n");
    scanf("%d", &sobremesa);
    int calbebida;
    printf("Escolha uma bebida: \n");
    printf("1-cha(20cal)\n");
    printf("2-suco de laranja(70cal)\n");
    printf("3-suco de melao(100cal)\n");
    printf("4-refrigerante diet(65cal)\n");
    scanf("%d", &bebida);
    
    
    {
		 if(prato == 1) += 180;
		 {
    else if(prato == 2) += 230;
		 }
    else if(prato == 3) += 250;
		 }
 {
 	else if(prato == 4) += 350;
 }
	
	return 0;

}
