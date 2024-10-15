#nclude <stdio.h>

int main()
{
int a;
int b;
int c;
printf("enter the 1st no");
scanf("%d",&a);
printf("enter the 2nd no");
scanf("%d",&b);
printf("enter the 3rd no");
scanf("%d",&c);
if(a>b && a>c){
    printf("a is greatest integar");}
    if(b>a && b>c){
        printf("b is greatest integar");}
    if(c>a && c>b){
        printf("c is greatest integar");}
    


    return 0;
}
