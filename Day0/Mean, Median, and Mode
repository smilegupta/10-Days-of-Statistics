#include<bits/stdc++.h>
using namespace std;


int main() {
    int tc;
    cin>>tc;
    vector<int> v;
    int x;
    for(int i=0; i<tc; i++)
    {
        cin>>x;
        v.push_back(x);
    }
    sort(v.begin(), v.end());
    double mean=0, median;
    
    for(int i=0; i<tc; i++)
    mean=mean+v[i];

    mean=mean/tc;
    cout << fixed << setprecision(1)<<mean<<endl;

    if(tc%2==0)
    {
        median=v[(tc/2)-1]+v[(tc/2)];
        median=median/2.0;
        cout << fixed << setprecision(1)<<median<<endl;
    }

    else{
    median=(int) v[(tc/2)-1];
    cout<<median<<endl;
}
int number = v[0];
int mode = number;
int count = 1;
int countMode = 1;

for (int i=1; i<tc; i++)
{
      if (v[i] == number) 
      {
         ++count;
      }
      else
      { 
            if (count > countMode) 
            {
                  countMode = count; 
                  mode = number;
            }
           count = 1; 
           number = v[i];
  }
}

cout<<mode;

    return 0;
}
