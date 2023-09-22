#include <stdio.h>
#include <stdlib.h>

void cong(float a, float b) {
    float sum = a + b;
    printf("\nTong: %f", sum);
    float minus = a - b;
    printf("\nHieu: %f", minus);
    float multiplication = a * b;
    printf("\nNhan: %f", multiplication);
    float divide = a / b;
    printf("\nChia: %f", divide);
}

int main(int argc, char *argv[]) {
    float a, b;
    printf("\nHay nhap gia tri cua a: ");
    scanf("%f", &a);
    printf("Hay nhap gia tri cua b: ");
    scanf("\n%f", &b);
    cong(a, b);
    return 0;
}
