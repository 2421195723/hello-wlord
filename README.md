# hello-wlord
just another repository
#include<iostream>
using namespace std;
int main1() {
	int N;
	cin >> N;
	int a[1000];
	for (int i = 1; i <=N; i++) {
		cin >> a[i];
	}
	int b[1000];
	
	for (int t = 1; t <= N; t++) {
		b[t] = 0;
		int j = t;
	while (j<=N) {
		b[t]+= a[j];
		j++;
	}
	cout << b[t] << " ";
	}
	return 0;
}
