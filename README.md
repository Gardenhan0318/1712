# 1712
STUDY
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main() {
    int a, b, c;
    scanf("%d", &a); //고정비용
    scanf("%d", &b); //가변비용
    scanf("%d", &c); //노트북 가격

    if (b >= c) printf("-1\n");
    else printf("%d\n", a / (c - b) + 1);
    return 0;
}
