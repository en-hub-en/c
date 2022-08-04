# c
#include<stdio.h>
int main(){
    int a=2;
    int b=1;
    int c=3;
    int tem=0;
    printf("%d %d %d",a,b,c);
    scanf("%d %d %d",&a,&b,&c);
if (a<b)
{
    tem=a;
    a=b;
    b=tem;
}else if (a<c)
{
    tem=a;
    a=c;
    c=tem;
}else if (b<c)
{
    tem=b;
    b=c;
    c=tem;
}

return 0;

}
