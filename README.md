# Average-of-3-Numbers-in-C

#include <stdio.h>

int main()

{
    
    int x, y, z, average;
    
    printf("Input 3 numbers to take the average of them.\n");
    
    printf("\n");
    
    scanf("%d", &x);
    
    printf("\n");
    
    scanf("%d", &y);
    
    printf("\n");
    
    scanf("%d", &z);
    
    printf("\n");
    
    average = (x + y + z) / 3;
    
    printf("\nThe average of %d, %d, and %d, is: %d.", x, y, z, average);

    return 0;
    
}
