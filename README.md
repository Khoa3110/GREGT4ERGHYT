#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */
struct Info{
char Name[50];
char Adress[50];
char Email[50];
int Age;
int Number;	
};
int main(int argc, char *argv[]) {
	struct Info IF;
printf("\nName: ");
scanf("%s", IF.Name);
printf("\nAdress: ");
scanf("%s", &IF.Adress);
printf("\nEmail: ");
scanf("%s", &IF.Email);
printf("\nAge: ");
scanf("%d", &IF.Age);
printf("\nNumber: ");
scanf("%d", &IF.Number);
FILE *fp;
fp = fopen("myinfor.txt", "w");
if(ferror(fp)) {
		printf("\nMo file bi error");
	} else {
	fprintf(fp, "Name:%s \nAdress:%s \nEmail:%s \nAge:%d \nNumber:%d", IF.Name, IF.Adress, IF.Email, IF.Age, IF.Number);
}fclose(fp);
return 0;}
