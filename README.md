# C-Program
**Print Hello World**
#include <stdio.h>
int main ()
{
    printf("Hello World");
    return 0;
}


**write a c program to read and display a character**
#include <stdio.h>
int main() {
    //write a c program to read and display a character
    char ch;
    printf("Enter a character: ");
    scanf("%c", &ch);
    printf("You entered: %c\n", ch);

    return 0;
}


**write a c program to read character and display its ASCII value**
#include <stdio.h>

int main() {
    //write a c program to read character and display its ascii value
    char ch;
    printf("Enter a character: ");
    scanf("%c", &ch);
    printf("The ASCII value of '%c' is: %d\n", ch, ch);

    return 0;
}
