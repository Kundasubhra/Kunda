#include <stdio.h>
#include <conio.h>
#include <string.h>

struct Emp
    {
        char name[30];
        int age;
        double salary;
    };
void swap(struct Emp, struct Emp*);
void sort(struct Emp[], int);
void main()
    {
        struct Emp x[10];
        int j;
        for(i=0;i<10;i++)
        {
            printf("Name=  ");
            scanf("%s", x[i].name);
            printf("age=");
            scanf("%d", &x[i].age);
            printf ("salary= ");
            scanf("%lf", &x[i].salary);
        }
        void swap(struct Emp *x, struct Emp *y)
        {
            struct Emp temp;
            temp = *x;
            *x = y;
            *y = temp;
        }
        void sort(struct Emp e[], int n)
    {
        int i,j;
        for(i=0;i<n-1;i++)
        {
            for(j=i+1;j<n;j++)
            {
                if(x[i].age<x[j].age)
                {
                    swap(&x[i],&x[j]);
                }
            }
        }
    }
        sort(x,10);
        printf("\n The sorted  list of Emplpyees  ");
        for(i=0;i<10;i++)
        {
            printf("%s,%d,%lf", x[i].name, x[i].age, x[i].salary);
        }
        getch();
    
