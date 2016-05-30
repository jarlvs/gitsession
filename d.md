jreguohgnj nljwghoh4n o4hho45 
lnbfbbt 4lthoh 4lkn5i55 lnl
nlt44;n lk4nnlkng 5lknnn 
fkkjbrj5l l5hhio5 l5kl5l
fkggi44 i5toi5t5t5
lkttlno itooi5o6oi
#include<iostream>
using namespace std;
int sum(int num){
	if(num>1)
    return num+sum(num-1);
    else 
    	return num;
}

int main()
{ 
	int a,b;
	cin>>a;
	b=sum(a);
	cout<<b<<endl;

	return 0;
	
}