#include<stdio.h>
#include<string.h>

int main()
{
  int a;
  scanf("%d",&a);
  
  //printf ("%d",a);
  
  void result(char name[10] , int cost)
  {
    
    printf("Food item - %s \nPrice -Rs %d", name,cost);
  }
  
  switch (a)
  {
    case 1 :
      result("Pizza",250);
      break;
    case 2 :
      result("Nachos",150);
      break;
    case 3 :
      result("Coffee",100);
      break;
    case 4 :
      result("Cheese cake",120);
      break;
    case 5 :
      result("Burger",200);
      break;
      
  }
  return 0;    
}
