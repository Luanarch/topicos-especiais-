# topicos-especiais-
atvidade1 topicos
#include <stdio.h>
#include <string.h>


int main ( ){
		float salario, aumento, salario_final;
		printf("* Empresa: CarPneus\n");	
		printf("* Ra: 201540155\n");
		printf("* Nome: Luan de Souza Mendonca\n");
		printf("------------------------------\n");
		printf("Informe seu salario:");
		scanf("%f", &salario);
		printf("------------------------------\n");
		printf("Salario informado:R$%.2f\n", salario);
		if (salario <= 1750){
			aumento = salario * 0.075 + 150;
			salario_final = salario + aumento;
			printf ("Seu salario teve um aumento provavel de: R$%.2f\n", aumento);
			printf("Seu salario proximado e de R$%.2f\n", salario_final);
		}else{
			aumento = salario * 0.075;
			salario_final = salario + aumento;
			printf ("Seu salario teve um aumento provavel de: R$%.2f\n", aumento);
			printf("Seu salario proximado e de R$%.2f\n", salario_final);
		}
		return 0;
}
