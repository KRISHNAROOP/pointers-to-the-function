# pointers-to-the-function
# array-to-pointers
#include<stdio.h>
int main()
{
   int a[3] = {1, 2, 3};
   int *p = a;    
   int i;
   for ( i = 0; i < 3; i++)
   {
      printf("%d, \t %d \n", p, *p);
      p++;
   }
   return 0;
}
