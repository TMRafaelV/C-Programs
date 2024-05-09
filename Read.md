// programa em C para calculo de idade baseado em ano

#include <stdio.h>
int resultado, ano_n,ano_a;

int _verif(int ano_n, int ano_a){

resultado = (ano_n - ano_a);

return resultado;
};

int main(){

printf("Informe o ano de nascimento ");
scanf("%d",&ano_n);
printf("Informe o ano atual ");
scanf("%d",&ano_a);
resultado = _verif(ano_a ,ano_n) ;

printf(" resultado %d",resultado);


};
