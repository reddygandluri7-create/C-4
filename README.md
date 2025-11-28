# C-4
#include<stdio.h>
int main(){
int a=10;
int *p;
p=&a;
printf("value of a=%d\n", a);
printf("address of a = %d \n", &a);
printf("value stored by p = %d \n ", p);
printf("value printed by p = %d \n", p);
return 0;
}
