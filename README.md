# SmallCap


Here is the code to find the capital of a small letter or small version of the capital letter!!


The best thing of this is, it also identifies the version of the letter you enter and replies you with the opposite form of it...
Cool right?!!!


This code is in c language.


#include <stdio.h>
int main()
{
    char c;
    printf("Enter a letter to find its capital or small version:");
    scanf("%c", &c);
    int asciiValue = c; // char is casted to an integer
    int num = asciiValue + 32;
    int mun = asciiValue - 32;
    char jim = num; // int value is casted to character
    char kim = mun; // same here too
    asciiValue<97 ? printf("The small letter of the entered capital letter is %c\n",jim) : printf("The capital letter of the entered letter is %c\n",kim);
    return 0;
}
