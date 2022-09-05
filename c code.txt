#include<stdio.h>
void main()
{
float vol,pd,mep,vs,rpm,n,nac,act,ns;
printf("enter the volume of the stroke");
scanf("%f",&vol);
printf("enter the nummber of cylinders");
scanf("%f",&ns);
printf("enter the power developed");
scanf("%f",&pd);
printf("enter the mean effective pressure");
scanf("%f",&mep);
vs=1.75/1000;
n=(pd*60)/(mep*vs);
nac=(rpm/2)*ns;
act=nac-n;
act=act/ns;
printf("The total number of misfire per minute=%f",act);
}                                                                                                                                                                                            
