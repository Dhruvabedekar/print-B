// print-B
//B
#include <stdio.h>
int main(){
	int r,s,n,i;
	for(r=1;r<=5;r++){
		if(r==1||r==3||r==5){
			for(s=1;s<=5;s++){
			printf("*");
		}
		}else{
			printf("*");
			for(i=0;i<3;i++){
			printf(" ");
		}
		printf("*");
		}
	
		printf("\n");
	}
	return 0;
}
