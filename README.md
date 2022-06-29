# codingNinjasPattern
 
 
     1
    232
   34543
  4567654
 567898765 
 
 code*****
 
 #include<iostream>
using namespace std;
int main(){
    int n;
    cin>>n;
    for(int i=1;i<=n;i++){
        int k=i;
        for(int j=0;j<n-i;j++){
            cout<<" ";
        }
        for(int j=0;j<i;j++){
            cout<<k++;
    }
     int l=2*(i-1);
    for(int j=0;j<i-1;j++){
        cout<<l--;
    }
    cout<<endl;
    }

     return 0;
}
