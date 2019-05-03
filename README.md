# Day-1
Move all zero's to end of the array



Program code:

# include <stdio. h>
# include <conio. h>
void main() 
{
int a[8] ;
int b[5] ; 
int c[5] ;
int i=7;
clrscr();
printf("Enter the elements (max=8)" ) ;
for(i=0;i<7;i++)
{
scanf("%d",&a[i]);
}
printf("The elements are:\n") ;

for(i=0;i<7;i++)
{
if(a[i]! =0 ) 
{
b[i]=a[i];
printf("%d\n",b[i]);
} 
}  

for(i=0;i<7;i++)
{
if(a[i]==0 ) 
{
c[i]=a[i];
printf("%d\n",c[i]);
} 
} 
getch() ;
} 

Output :

Enter the elements (max=8) 
1
0
2
5
0
7

The elements are

1
2
5
7
0
0
