#include<stdio.h>
int main(){
int n;
printf("Enter the valof n :");
scanf("%d",&n);
printf("Enter the ele: \n",n);
int arr[n];
for(int i=0;i<n;i++){
    scanf("%d", arr[i]);
}
int i1,i2;
printf("Enter 2 indices to swap");
scanf("%d %d", &i1,&i2);
if(i1>=0 && i1<n && i2>=0 && i2<n) {
    int temp =arr[i1];
    arr[i1]=arr[i2];
    printf("After Swapping :\n");
    for(int i=0;i<n;i++){
        printf("%d ", arr[i]);
    }
    }else{
    printf("Invalid indices");
    }
return 0;
}
