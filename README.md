# Number-Calculator
Created calculator with the help of C programming
#include<stdio.h>
int main()
{
      int  a,b;
      
      printf("Enter TWo Number : ");
      scanf("%d%d",&a,&b);

      printf("\nFor Sum press 1\n");
      printf("For Subtract press 2\n");
      printf("For Product press 3\n");
      printf("For Division press 4\n\n");
      
      int num;
      scanf("%d",&num);

      if(num == 1){
            printf("\nSummation : %d",a+b);
      }
      else if(num == 2){
            printf("\nSubtraction : %d\n",a-b);
      }
      else if(num == 3){
            printf("\nProduct : %d",a*b);
      }
      else if(num == 4){
            if(b == 0){
                  printf("\nNot Void Input");
            }
            else{
            printf("\nDivision : %d",a/b);
            }
      }
      else{
            printf("\nInvalid!!!");
      }

      return 0;
} 
