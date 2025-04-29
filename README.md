EXP NO:1 C PROGRAM FOR ARRAY OF STRUCTURE TO CHECK ELIGIBILITY FOR THE VACCINE.

Aim: To write a C program for array of structure to check eligibility for the vaccine person age above 6 years of age.

Algorithm:

Declare structure eligible with age (integer) and n (character array)
Declare variable e of type eligible
Input age and name using scanf, store in e
If e.age <= 6
Print "Vaccine Eligibility: No" Else
Print "Vaccine Eligibility: Yes"
Print details (e.age, e.n)
Return 0

##Program:
```

#include<stdio.h> 
struct eligib 
{ 
int age; 
char n[4]; 
}; 
int main() 
{ 
struct eligib e; 
scanf("%d%s",&e.age,e.n); 
if(e.age<=6) 
{ 
printf("Age:%d\nName:%svaccine:%d\neligibility:no",e.age,e.n,e.age); 
} 
else 
{ 
} 
 
printf("Age:%d\nName:%svaccine:%d\neligibility:yes",e.age,e.n,e.age); 
 
}

```
Output:
![7](https://github.com/user-attachments/assets/5a1175d7-d1cd-45ff-870d-37227fe2d470)

Result: Thus, the program is verified successfully.
