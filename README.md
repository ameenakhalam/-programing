# -programing
it is my programming excercise
Array creation in c

#include <stdio.h>

int main(void) {
  int limit;int i;int array[12];
  printf("Enter the array size");
  scanf("%d",&limit);
  printf("Enter the values");
  for(i=0;i<limit;i++)
  {
    scanf("%d",&array[i]);
  }
  printf("Entered values are\n");
  for (i=0;i<limit;i++){
printf("%d\n",array[i]);
  }
  return 0;
}
