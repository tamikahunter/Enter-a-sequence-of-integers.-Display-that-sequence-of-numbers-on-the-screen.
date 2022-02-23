# Enter-a-sequence-of-integers.-Display-that-sequence-of-numbers-on-the-screen.
Enter a sequence of integers. Display that sequence of numbers on the screen.
#include<stdio.h>
#include<conio.h>
main()
{    
    int a[50];
    int i,n;
    printf("Nhap so phan tu mang: ");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }    
    printf("\nMang vua nhap la:");
    for(i=0;i<n;i++)
    {
        printf("%5d",a[i]);
    }
    getch();
}
