#include <stdio.h>
struct employee{
    char id[4];
    char company[10];
};

int main()
{
    struct employee *ptr;
    int i;
    ptr = (struct employee *)malloc(sizeof(struct employee)*4);
    for(i=0;i<4;i++)
    {
        scanf("%s  %s",(ptr+i)->id,(ptr+i)->company);
    }
     for(i=0;i<4;i++)
    {
        printf("%s  %s\t",(ptr+i)->id,(ptr+i)->company);
    }


    return 0;
}

