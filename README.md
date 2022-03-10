# ALUNO-APROVADO-OU-REPROVADO-
#include <stdio.h>
#include <stdlib.h>

int main()
{
    //Declaração das variáveis
    int notaA, notaB; 
    double media;  
    
    //Solicitando os dados do usuários e atribuir os dados nas variáveis
    printf ("Digite a primeira nota do aluno: ");
    scanf ("%d", &notaA);
    
    printf ("Digite a segunda nota do aluno: ");
    scanf ("%d", &notaB);
    
        //Calculo da média
        media = (notaA + notaB)/2;
    
            //Verificação condicional
            if (media >= 6) {
               printf ("A nota do aluno foi: %.2lf, a primeira nota foi: %d \n", media, notaA); 
               printf("Aprovado\n"); 
               
            } else {
                
               printf("Reprovado\n"); 
            }
    
    return 0;
}
