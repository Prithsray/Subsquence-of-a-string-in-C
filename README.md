# Subsquence-of-a-string-in-C
This code is to find out the subsequences in a string

#include <stdio.h>
#include <string.h>
int main() {
     char a[1000];
    printf("enter the character> ");
    scanf("%s",a);
    printf("enter the character> ");
    scanf("%s",&b);
    int x,y;
    for(x=0;x<=strlen(a);x++){
        for(y=0;y<=strlen(a);y++){
            t[x] = a[y],a[x];
            printf("%c %c",a[y],a[x]);
        }
       
    }
        return 0;
}
