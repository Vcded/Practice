#include <stdio.h>
#pragma warning(disable: 4996)

int main() {
    int a = 0;
    int b = 0;
    printf("Enter two numbers(leave a space between the two numbers):  ");
    scanf_s("%d", &a);
    scanf_s("%d", &b);
    printf("The numbers entered are: %d and %d", a, b);

        return 0;
}