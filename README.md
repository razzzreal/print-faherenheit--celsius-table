#include <stdio.h>
void main()
{
    float fahr,cel;
    int lower ,upper,step;
    lower=0;
    step=20;
    upper=300;
    fahr==lower;
    while(fahr<=upper)
    {
        cel=5*(fahr-32)/9;
        printf("%f\t %f\n",fahr,cel);
        fahr=fahr+step;
    }
}
