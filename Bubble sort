//
//  main.cpp
//  Sorting
//
//  Created by Pratik P Devlekar on 3/22/19.
//  Copyright © 2019 Pratik P Devlekar. All rights reserved.
//

#include <iostream>
using namespace std;

void swap(int *a,int *b)
{
    int tmp=*a;
    *a=*b;
    *b=tmp;
}


void bs(int arr[],int n)
  {
   for(int i=0;i<n;i++)
     for(int j=0;j<n-i-1;j++)
   
        if(arr[j]>arr[j+1])
        swap(&arr[j],&arr[j+1]);
    
  }

int main()
{
    int n,i;
    cin>>n;
    int a[n];
    for(i=0;i<n;i++)
        cin>>a[i];
    bs(a,n);
    cout<<"Sorted Array"<<endl;
    for(i=0;i<n;i++)
        cout<<a[i]<<"\t";
}


