#include<stdio.h>
 
int main() {
   int a[30], i, num, smallest, biggest;
 
   printf("\nEnter no of elements :");
   scanf("%d", &num);
 
   //Read n elements in an array
   for (i = 0; i < num; i++)
      scanf("%d", &a[i]);
 
   //Consider first element as smallest
 
  
  smallest=a[0];
  for (i = 0; i < num; i++) {
   	  if(a[i]>0)
      if (a[i] < smallest) {
         smallest = a[i];
      }
   }

 
  biggest = a[0];
  for (i = 0; i < num; i++) {
       if(a[i]<0)
      if (a[i] > biggest) {
         biggest = a[i];
      }
     
   }

   
 
   // Print out the Result
   printf("\nhamgiin baga eyreg too : %d", smallest);
   printf("\nhamgiin ih surug too: %d", biggest);
 
   return (0);
}
