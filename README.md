#include<stdio.h>
#include<conio.h>
void main()
{
      int physiscs,chemistry,biology,mathematics,computer;
      float percentage;
      
      printf("enter mark of physics subject:");
      scanf("%d",&phisics);
      printf("enter mark of chemistry subject:");
      scanf("%d",&chemistry);
      printf("enter mark of biology subject:");
      scanf("%d",&biology);
      printf("enter mark of mathematics subject:");
      scanf("%d",&mathematics);
      printf("enter mark of computer subject:");
      scanf("%d",&computer);
      
      percentage=( (physics+chemistry+biology+mathematics+computer)/5.0);
      printf("\n. percentage:%2f \n", percentage);
      
      if(percentage>100)
        {
            printf("
            invalid marks assigned");
        }
    else
    if(percentage>90 && percentage<=100)
       {
           printf("grade A \n");
       }
    else
    if(percantage>80 && percentage<90)
       {
           printf("grade B \n");
       }
    else
    if(percentage>70 && precentage<80)
       {
           printf("grade C \n");
       }
    else
    if(percentage>60 && percentage<70)
       {
           printf("grade D \n");
       }
    else
    if(percentage>40 && percentage<60)
       {
           printf("grade F \n");
       }
       getch();
}
