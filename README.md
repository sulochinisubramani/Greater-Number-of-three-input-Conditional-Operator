# Greater-Number-of-three-input-Conditional-Operator-C
#C program
#Print the greater number of three input integer using Conditional Operator. In this program, greater number is find without using Conditional Statement(if-else),Relational Operator(>).   
#include <stdio.h>
void main(){
    int a,b,c;
    printf("Enter the three numbers:");
    scanf("%d %d %d",&a,&b,&c);
    (a>b && a>c) ? printf("a is greater number") : (b>c) ? printf("b is greater number") : printf("c is greater number");
}
