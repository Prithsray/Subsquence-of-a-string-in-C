# Subsquence-of-a-string-in-C
This code is to find out the subsequences in a string

#include <stdio.h>
#include <string.h>
int main() {
     char a[1000];
      int x,y;
    printf("enter the character> ");
    scanf("%s",a);
    for(x=0;x<=strlen(a);x++){
        for(y=0;y<=strlen(a);y++){
            t[x] = a[y],a[x];
            printf("%c %c",a[y],a[x]);
        }   
    }
        return 0;
}
