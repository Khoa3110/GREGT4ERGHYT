#include <iostream>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char** argv) {


float max(float x, float y);
void main()
{
    float MAX;
    float a, b, c, d;
    printf("\nNhap a: ");
    scanf("%f", &a);
    printf("\nNhap b: ");
    scanf("%f", &b);
    printf("\nNhap c: ");
    scanf("%f", &c);
    printf("\nNhap d: ");
    scanf("%f", &d);
 
    MAX = max(max(a, b), max(c, d));
    printf("\nMAX(%f,%f,%f,%f) = %f", a, b, c, d, MAX);
    getch();
}
 
float max(float x, float y)
{
    float max;
    if(x > y)
        max = x;
    else
        max = y;
    return max;
}
return 0;
}
