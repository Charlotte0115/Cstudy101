# Cstudy101
#include <stdio.h>

int main(void)
{
    int age;
    double height;
    double weight;
    
    printf("나이와 키와 몸무게를 입력하세요 : ");
    scanf("%d%lf%lf", &age, &height, &weight);
    printf("나이는 %d살, 키는 %.1lfcm, 몸무게는 %lfkg입니다\n", age, height);
    
    return 0;
}
