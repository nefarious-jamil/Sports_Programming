#include <iostream>
using namespace std;

int main() {

	long long a,b; cin>>a>>b;
	while(b--){
	    a = (a%10==0)? a/10:--a; 
	}
	cout<<a<<endl;
	return 0;
}
