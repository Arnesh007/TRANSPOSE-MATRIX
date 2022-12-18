# TRANSPOSE-MATRIX
write a program to perform transpose given 2D matrix.

Input & Output Format:

Input consists of one integer and one matrix.

First input consists of a row and a column.

Second give the array elements as a matrix based on their size of row and column.

Output consists of a transposed matrix.

Sample Input:
3

1 2 3

4 5 6

7 8 9

Sample Output:

Transpose matrix is :

1 4 7 

2 5 8 

3 6 9 

ANSWER:
#include<iostream>
using namespace std;
int main()
{
     int i,j,n;
     cin>>n;
     int a[n][n];
     
     
     for(i=0;i<n;i++)
     {
         for(j=0;j<n;j++)
         {
            cin>>a[i][j];
        }
     }
       cout<<"Transpose matrix is:";
     for (j=0;j<n;j++)
     {
         for(i=0;i<n;i++)
         {
             cout<<a[i][j]<<" ";
             
         }
     }cout<<endl;
         
}
