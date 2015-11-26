#include <iostream>
#include <stdlib.h>
#include <math.h>  
using namespace std;
int main(){
	int amount;
	
	cin>>amount;
	int ans[amount];
	for(int p = 0; p<amount; p++){
		int num[6];
		//int num[] = {4,6,9,10,15,25};
		//int num[] = {1,2,3,4,5,6};
		for(int z = 0; z<6; z++){
			cin>>num[z];
		}
		int a = num[0], b = num[1], c = num[2], d = num[3], e = num[4], f = num[5], total = 0;
		int sq = sqrt(a*b*c*d*e*f);
		if(a*b*c == sq)
			total++;
		if(a*b*d == sq)
			total++;	
		if(a*b*e == sq)
			total++;
		if(a*b*f == sq)
			total++;
		if(a*c*d == sq)
			total++;
		if(a*e*c == sq)
			total++;
		if(a*f*c == sq)
			total++;
		if(a*d*e == sq)
			total++;
		if(a*f*d == sq)
			total++;
		if(a*e*f == sq)
			total++;
		ans[p] = total;
	}
	for(int s=0; s<amount; s++){
		cout<<ans[s];
		cout<<"\n";
	}
}
