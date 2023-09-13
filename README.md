#include <iostream>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char** argv) {


//(ax2 + bx + c = 0)
int a,b,c;
printf("\n Hay nhap gia tri cau a = ");
scanf("%d", &a);
printf("\n Hay nhap gia tri cau b = ");
scanf("%d", &b);
printf("\n Hay nhap gia tri cau c = ");
scanf("%d", &c);
if(a == 0) {

        if(b == 0) {
            if (c == 0) {
                printf("\nPhuong trình co nhieu nghiem.\n");
            } else {
                printf("\nPhuong trình vô nghiem.\n");}}}


// CON CHIU THUC SU

return 0;
}
