# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
## DATE:
## AIM:
To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to read a file name from user and create that file and insert student
roll numbers in to that file.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.

## Program:
```
/*
C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.
Developed by: Karthick Kannan SP
RegisterNumber: 212222060114
*/
#include <stdio.h>
int main()
{
    FILE *f;
    f=fopen("Hospital.txt","w");
    if(f==NULL)
    printf("Unable to create or open the file.\n");
    else
    printf("File Created Successfully\n");
    printf("File Opened\n");
    fclose(f);
    printf("File Closed");
}
```

## Output:
![image](https://github.com/user-attachments/assets/49e5ccb5-5bea-49e7-8e29-20d70e7c47e7)




## Result:
Thus the program was executed and the output was verified successfully.
