# -C-horrors
//started with C ------> should end up with next OS jk!!!!!!!

//my first program. Much of a great effort....

#include<stdio.h>
int main()

{

	char a;
	
	int val ,i,j;
	
	printf("enter the number of alphabets u want  \n");
	
	scanf("%d",&val);
	
	for(i= 0 ;i<val;i++)
	
	{
	
		a='A';
		
		if(i%2==0)
		
		{
		
			for(j=0;j<i+1;j++)
			{
				if(j%2==0)
					printf("%c",a);
				else
					printf("%c",a+32);
			a++;
			}
		}
		else
		{
			for(j=0;j<i+1;j++)
			{
				if(j%2==0)
					printf("%c",a+32);
				else
					printf("%c",a);
			a++;
			}
			
		}
		

		printf("\n");
	}
	return 0;
}


//output is like

/* enter the number of alphapets u want 
5
o/p

A

aB

AbC

aBcD

AbCdE*/
