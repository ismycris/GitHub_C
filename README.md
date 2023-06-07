# GitHub_C
/*exer 14
Crie um programa com um vetor de 10 posições chamado TABUADA. 
O usuário deverá fornecer um número inteiro, e seu vetor deve 
ser preenchido (automaticamente) com a tabuada desse número, 
em seguida imprima a tabuada*/
#include <stdio.h>
#include <stdlib.h>

int main()
{
    // criação das variáveis
    int tabuada[10];
    int i;
    printf("\nDigite a tabuada que voce deseja \n\t ");
    scanf("%i", &tabuada[i]);
  // repetição para ler valores do teclado
    for(int x = 1; x<=10; ++x)
    {
 // impressão do vetor
        //1 x 5 = 5
        printf("%ix%i = %i\n", x, tabuada[i], x * tabuada[i]);
    }


    return 0;
}
