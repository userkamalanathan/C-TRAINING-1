#include <stdio.h>

int main()
{
    float p;
    printf("enter the value of p:");
    scanf("%f",&p);
    float n;
    printf("enter the value of n:");
    scanf("%f",&n);
    float r;
    printf("enter the value of r:");
    scanf("%f",&r);
    float si=p*n*r/100;
    printf("%.2f",si);
    
    

    return 0;
}
