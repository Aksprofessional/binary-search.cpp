# binary-search.cpp
//(BINARY SEARCH) C program to find location(index) of a no. in a array and printing the no. of times is there in array with elements in increasing order.if not present in array, then not found is printed.
//(BINARY SEARCH) C program to find location(index) of a no. in a array and printing the no. of times is there in array with elements in increasing order.if not present in array, then not found is printed.


#include <stdio.h>

int main() {
    int i,n,s,flag;
    int a[]={3,6,3,9,12,6,3,4,2};
    printf("array of 9 elements is created:\n");
    for(i=0;i<8;i++)
    printf("%d\n",a[i]);
    printf("enter no. to be founded=");
    scanf("%d",&n);
    s=0;
    for(i=0;i<9;i++)
     if(n==a[i]){
      printf("given no. is founded at location %d\n",i);
      s=s+1;
     }
    
    printf("no. is present %d times\n",s);
     
    if(s==0)
    printf("hence,no. not found");
    return 0;
}
