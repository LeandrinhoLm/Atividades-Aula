#include <stdio.h> 
int main (){
	int notas [5] = {7, 8, 6, 9, 10};
	int soma = 0;
	for(int i = 0; i < 5; i++){
		soma += notas[1];
	}
	float media = soma / 5.0;
	printf("Media das notas = %.2f\n", media);
	return 0;
}

