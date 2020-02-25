#include<bits/stdc++.h>
using namespace std;


int main() {
    int tc;
    cin>>tc;
    vector<int> smile;
    vector<int> shivanshu;
    int x;
    for(int i=0; i<tc; i++ )
    {
        cin>>x;
        smile.push_back(x);
    } 
    for(int i=0; i<tc; i++ )
    {
        cin>>x;
        shivanshu.push_back(x);
    } 
    double mean=0;
    
    for(int i=0; i<tc; i++ )
    {
        mean=mean+(smile[i]*shivanshu[i]);
    }
    int sum=0;
    for(int i=0; i<tc; i++ )
    {
        sum=sum+shivanshu[i];
    }
    mean=mean/sum;
    cout<<fixed<<setprecision(1)<<mean;

    return 0;
}
