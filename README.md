# 14
#include <iostream>
using namespace std;

int num(int n)
{
    int i;
    if(n==1) i=1;
    else i=2*(num(n-1)+1);
    return i;
}

int main()
{
    cout<<"桃子一共有："<<num(10)<<"个"<<endl;
    return 0;
}
