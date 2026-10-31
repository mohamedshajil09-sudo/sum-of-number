# sum-of-
// Online C compiler (editor)
// Write and run C online using this editor.

#include <stdio.h>

int main() {
 int n,sum=0,fun;
 printf(" enter the number :");
 scanf(" %d",&n);
 for( ;n>0;){
     fun= n%10;
     sum=sum+fun;
    n =n/10;
 }
    printf("%d",sum);
    return 0;
}
