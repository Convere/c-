#include <iostream>
using namespace std;
//冒泡排序
int main()
{
int score[]={78,97,87,56,87,98,86,93,91,82,72};
  for(int i = 10;i >= 0;i--) //从小到大排列
  {
    for(int j = 0;j <= i;j++)
      {
         if(score[j]>score[j+1])
         {
          int temp;
          temp = score[j];
          score[j] = score[j+1];
          score[j+1] = temp;
         }   
       } 
   }
  for(int a=0;a <= 10;a++)
  { 
  cout << score[i]<< endl;
  }                      
}  
