#include <stdio.h>
#include <stdlib.h>

int main()
{
    int a[3][4]={ 1,2,3,4,5,6,7,8,9,10,13,12};

    printf("%u \n %u \n %u",a[0]+1,*(a[0]+1),*(*(a+0)+1));
    return 0;
}
