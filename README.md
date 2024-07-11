# find-the-length-of-the-string-within-scanf-in-c-programming
#find the length of the string 's' without using loop or strlen function in c programming
#include <stdio.h>

int main() {
    char str[100];
    int len;
    printf("Enter a string: ");
    scanf("%99s%n", str, &len);
    printf("String length: %d\n", len);
    return 0;
}

