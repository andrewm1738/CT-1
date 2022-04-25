# CT-1
#include <stdio.h>
#include <math.h>
int main(){
float b,Ms,rs1,rs2;
scanf("%f%f",&b,&Ms);
b=b*b
Ms=Ms*Ms;
rs1=sqrt(Ms-b);
rs2=sqrt(Ms+b);
printf("%.5f %.5f",rs1,rs2);
return 0;}
