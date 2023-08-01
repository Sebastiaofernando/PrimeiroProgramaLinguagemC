# PrimeiroProgramaLinguagemC
 LógicadePeogramaçãoC

#include <stdio.h>
int main() {
	int num1, num2, soma, diferenca, produto, divisao;
	printf("Digite o primeiro numero:\n", num1);
	scanf("%i",&num1);
	printf("Digite o segundo numero:\n", num2);
	scanf("%i",&num2);
	
	soma = num1 + num2;
	
	diferenca = num1 - num2;
	
	produto = num1 * num2;
	
	divisao = num1 / num2;
	
	printf("A soma e: %i\n", soma);
	
	printf("A subtracao e : %i\n", diferenca);
	
	printf("O produto e : %i\n", produto);
	
	printf("A divisao e : %i\n", divisao);
	
	return 0;
}
