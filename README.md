# c
#include<stdio.h>
int main(){
int ret=0;
int cha=0;
char password[20]={0};
  printf("请输入密码：");
  scanf("%s",password);
  while((cha=password)!='/n'){
  
  };//这样才能执行下面的操作
  printf("请确认：（y/n）")；
   while(ret=='y'){
    printf("确认成功")；
   }else{
    printf("放弃确认")；
   }
}
