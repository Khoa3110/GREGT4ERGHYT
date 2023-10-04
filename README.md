#include <iostream>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char** argv) {
int IsPrime = 0, a;
int n=0;
int i;
int p;
printf("Please enter the number n: ");
scanf("%d", &IsPrime);
n = IsPrime/2;
for(i = 2; i<=n; i++){
	if(IsPrime%i==0){
		printf("%d isn't a prime number", IsPrime);
	p = 1	;
	}
	break;
}
if(p ==0){
	printf("%d is a prime number", IsPrime);
}
		return 0;
}
