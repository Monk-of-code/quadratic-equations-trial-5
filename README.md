# quadratic-equations-trial-5
#include <stdio.h>
#include<math.h>
int main()

{
    double a,b,c,root_1 ,root_2;
    printf(" fill in a\n");
    scanf("%1f",&a);
    printf("fill in b\n");
    scanf("%1f",&b);
    printf("fill in c\n");
    scanf("%1f",&c);
    root_1 = (-b+sqrt(b*b - 4*a*c))/(2*a);
    root_2 = (-b- sqrt(b*b - 4*a*c))/(2*a);
    printf("\n the first root  = %1f\n",root_1);
    printf("\n the second root = %1f \n",root_2);
    return 0;
}
