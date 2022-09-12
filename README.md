# binary-conversion
/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>

int main()
{
    int a,rev=0,dig,i=1;
    printf("Enter your number:");
    scanf("%d",&a);
    while(a!=0){
        dig=a%2;
        rev=rev+(dig*i);
        i=i*10;
        a=a/2;
    }
printf("binary num is%d ",rev);
    return 0;
}
