# First-Program

 /* This program helps in finding whether a nubmer entered ends with a zero or not */
 
 #include <stdio.h>
 #include <stdlib.h>
 
 int main () {
    int n;
 
    printf("Enter a number:");
    scanf("%d" , &n);
    
    if (n%10 == 0) {
        printf("The number entered ends with a 0");
        }
    else {
        printf("The number entered does not end with a 0");
        }
 
    return(0);
}
