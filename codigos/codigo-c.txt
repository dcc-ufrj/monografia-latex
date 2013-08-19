#include <stdio.h>
#define N 10

/**
 * Block
 * Comment
 *
 **/
 
int main()
{
  // line comment
  int i, x;
  
  scanf("%d", &x);
  
  if (x == 0) {
    return -1;
  }
  
  while (x--) {
    for (i = 0; i < x; i++) {
      printf("%d ", i);
    }
  }
  
  return 0;
}