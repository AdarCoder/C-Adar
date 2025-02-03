# C-Adar
//wAP to check weather a number is odd or even
#include <stdio.h>
int main() {
    int n;
    printf("Enter a number: ");
    scanf("%d", &n);
    if (n % 2 == 0){
        printf("The number %d is even.\n",n);
        
    }else{
        printf("The number %d is odd.\n",n);
    }
    return 0;
}
