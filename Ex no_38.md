# # Task

# # Given a positive integer denoting , do the following:

# If  71<=n <=79 print the lowercase English word corresponding to the number (e.g., seventy one for 71 , seventy two for 72 etc.).
If n>79 print Greater than 99.
## Input Format

The first line contains a single integer, .

## Constraints

## Output Format

If   71<=n <=79 print the lowercase English word corresponding to the number (e.g., seventy one for 71 , seventy two for 72 etc.).
If n>79 print Greater than 79.
## Sample Input

71
## Sample Output

seventy one
## Sample Output

seventy one

## AIM:
To write a program to print the English word corresponding to the given number.

## ALGORITHM:
1. Start.
2. Define a variables.
3. Write a program to print the English word corresponding to the given number.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
   
## PROGRAM:
```c
#include <stdio.h>
int main()
{
    int n;
    scanf("%d", &n);
    if(71<=n && n<=79)
    {
        printf("seventy ");
        switch(n)
        {
            case 71:
            printf("one"); 
            break;
            case 72:
            printf("two"); 
            break;
            case 73:
            printf("three"); 
            break;
            case 74:
            printf("four"); 
            break;
            case 75:
            printf("five"); 
            break;
            case 76:
            printf("six"); 
            break;
            case 77:
            printf("seven"); 
            break;
            case 78:
            printf("eight"); 
            break;
            case 79:
            printf("nine"); 
            break;
        }
    }
    else
    printf("Greater than 79");
    return 0;
}
```
## OUTPUT
<img width="832" height="252" alt="image" src="https://github.com/user-attachments/assets/49878869-d992-43b8-8076-b42153ff7d09" />
## RESULT:
Thus, the program is executed and verified successfully
