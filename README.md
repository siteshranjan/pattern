# pattern
simple pattern problem
@@ -0,0 +1,35 @@
#include<stdio.h>
#include<conio.h>
void main()
{
	int i,j,n;
	scanf("%d",&n);
	for(i=1;i<=n;i++)
	{
	   for(j=1;j<=n;j++)
	   {
	   
		
		if ((i==1) || (i==n))
		{
		
		
		printf("*");
	
	}
	
	    else
       {
       
	   if((i+j)==(n+1))
	   {
	   
	   printf("*");
}
	   else{
	   
	   printf(" ");	}
}
}	printf("\n");
}
}
