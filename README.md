#include <stdio.h>
int main()
{
    int age;
    float height;
    double weight;
    char grade;
    printf("Enter your age: ");
    scanf("%d", &age);
    printf("Enter your height in cm: ");
    scanf("%f", &height);
    printf("Enter your weight in kg: ");
    scanf("%lf", &weight);
    printf("Enter your grade: ");
    scanf(" %c", &grade);
    printf("\n----- Student Information -----\n");
    printf("Age: %d years\n", age);
    printf("Height: %.2f cm\n", height);
    printf("Weight: %.2lf kg\n", weight);
    printf("Grade: %c\n", grade);
    return 0;
}
