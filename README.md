# CheckForPrime
code is implemented in c++;
   #include<iostream>
#include<limits.h>
using namespace std;
bool isPrime(int n )
{
    if(n==1)
        return false;
    for(int i = 2;i*i<n;i++){
        if(n%i==0)
            return false;
    } return true;
}
int main()
{
    int n;
    cin>>n;
    cout<< (bool)isPrime(n);
    return 0;
}

// code with brdcoder007
