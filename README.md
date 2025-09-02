#include <stdio.h>

int main() {
    int number;
    printf("enter the number : ");
    scanf("%d",&number);
    if (number%2==0){
        printf("EVEN");
    }
    else{
        printf("odd");
    }
    return 0;
}
