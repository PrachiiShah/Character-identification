# Character-identification
To identify an input character as vowel or consonant.
Hey, this programme will help you to judge the nature of a character.
#include<stdio.h>
#include<conio.h>
void main()
{
char input;
printf("Enter a single character");
scanf("%c",&input);
if(input == a || e || i || o || u)
{
printf("The input character %c is a vowel", input);
}
else
{
printf("The input character %c is a consonant", input);
}



