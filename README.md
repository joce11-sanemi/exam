#include <stdio.h>
#include <math.h>

int main(){
    printf("this program is a simple calculator");
    float num1;
    float num2;
    char oper;
    printf("\n write your operation: ");
    scanf("%f %c %f", &num1, &oper, &num2);
    if (oper == '+'){
        printf("\n The result is: %f", num1 + num2);
    } else if (oper == '-'){
        printf("\n The result is: %f", num1 - num2);
    } else if (oper == '*'){
        printf("\n The result is: %f", num1 * num2);
    } else if (oper == '/'){
        printf("\n The result is: %f", num1 / num2);
    }
    printf("\n Thanks for using our program :)";
    return 0;
    
}# exam
programs 
