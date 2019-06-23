# submit50-cs50-2019-x-mario-more 
#include <cs50.h>
#include <stdio.h>

int main(void)
{int h;
 do
 {
     h=get_int("hieght:");
 }while(h<1 || h>8);
     printf("stored:%i\n",h);

 
for(int i=0;i<h;i++)
{for(int j=h-i;j>1;j--)
{
    printf(" ");
} 
 for(int k=0;k<=i;k++)
 {
     printf("#"); 
    
    
 } printf("  "); 
 for(int l=0;l<=i;l++)
 {
     printf("#");
 }
 printf("\n");
    
}}
