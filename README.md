# Olympick12 
#include<stdio.h>
#include<conio.h>
     void indaypibonaci (int n,long a,int b)
     {
     
     	int  t;
     	if(n>0)
		 {  
		 t = a+b;
		 printf("%d \n",t);
		 indaypibonaci (n-1,b,t);
		 
     		
		 }
     	
	 }
	 int main ()
	 {
	 	int a;
	 	printf("nhap a:"); scanf("%d",&a);
	 	printf("daypibonaci: \n");
	 	indaypibonaci(a,1,0);
	 	getch();
	 }
