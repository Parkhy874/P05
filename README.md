# P05
프로그래밍응용 | 과제3 - 프로그래밍5

#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	int x, iNum1, iNum2;

	printf("정수를 입력하시오: ");
	scanf("%d", & x);

	iNum1 = x / 10;
	iNum2 = x % 10;

	printf("십의 자리: %d\n", iNum1);
	printf("일의 자리: %d\n", iNum2);

	return 0;
}
