#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */
struct HinhChuNhat {
    float dientich;
    float chieurong;
    float chieudai;
};

int main(int argc, char *argv[]) {
    int i;
    struct HinhChuNhat HCN[5];

    for (i = 0; i < 5; i++) {
        printf("\nHay nhap vao chieu rong cua HCN %d: ", i + 1);
        scanf("%f", &HCN[i].chieurong);

        printf("\nHay nhap vao chieu dai cua HCN %d: ", i + 1);
        scanf("%f", &HCN[i].chieudai);
    }
    float sum;
for(i=0; i<5; i++){
	printf("\nDien Tich hinh chu nhat %d: ", i + 1);
	HCN[i].dientich = HCN[i].chieurong * HCN[i].chieudai;
	printf("%f", HCN[i].dientich);
	printf("\n");
	sum = sum + HCN[i].dientich;
};
printf("Tong cua dien tich cac hinh chu nhat la %f", sum);
    return 0;
}
