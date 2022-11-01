# algoritmo-sj
Intervalo //

#include<stdio.h>
int n;

int main(){
printf ("digite um numero:");
scanf("%d",&n);
switch(n){
case -10 ... 0:
printf("\nintervalo entre -10 e 0");
break;
case 1 ... 11:
printf("\nintervalo entre 1 e 11");
break;
case 12 ... 24:
printf("\nintervalo entre 12 e 24");
break;
case 25:
printf("\nintervalo 25");
break;
default:
	printf("\nnumero fora do intervalo ");
}

return 0;	
}

