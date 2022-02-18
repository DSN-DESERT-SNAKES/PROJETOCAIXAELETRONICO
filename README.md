# PROJETOCAIXAELETRONICO
CODIGO FONTE CAIXA ELETRONICO COM NOTAS DE 100 A 1 R$
#include <stdio.h>
#include <math.h>
int main(){
	int total, nota100, nota50, nota20, nota10, nota5, nota2, nota1;
	scanf("%d", &total);
	nota100 = 0;
	while (total >= 100) {
		total = total - 100;
		nota100 = nota100 + 1;
	}
	printf("%d nota(s) de R$ 100,00\n", nota100);

	nota50 = 0;
	while (total >= 50) {
		total = total - 50;
		nota50 = nota50 + 1;
	}
	printf("%d nota(s) de R$ 50,00\n", nota50);
	
	nota20 = 0;
	while (total >= 20) {
		total = total - 20;
		nota20 = nota20 + 1;
	}
	printf("%d nota(s) de R$ 20,00\n", nota20);

	nota10 = 0;
	while (total >= 10) {
		nota10 = nota10 - 10;
		nota10 = nota10 + 1;
	}
	printf("%d nota(s) de R$ 10,00\n", nota10);

	nota5 = 0;
	while (total >= 5) {
		nota5 = nota5 - 5;
		nota5 = nota5 + 1;
	}
    printf("%d nota(s) de R$ 5,00\n", nota5);
	nota2 = 0;
	while (total >= 2){
		nota2 = nota2 - 2;
		nota2 = nota2 + 2;
	}
	printf("%d nota(s) de R$ 2,00\n", nota2);

	nota1 = 0;
	while (total >= 1){
		nota1 = nota1 - 1;
		nota1 = nota1 + 1;
	}
	printf("%d nota(s) de R$ 1,00\n", nota1);
	
	return 0;
}
