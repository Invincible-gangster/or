#include <stdio.h>

int main() {
	int a = 12,b=13,c=14,d;
	d=(a++ || ++b || ++c);
	printf("%d %d %d %d",a,b,c,d);
}
