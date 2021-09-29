# mashqlar

// ikkita idishda t1 v1 va t2 v2 hajimli va haroratli suv bor ikkisi bir idishga solindi hosil bo'lgan aralashmaning
umumiy hajmi va o'rtacha haroratini topish formulasi

#include<iostream>

using namespace std ;

int main () {
	int t1 , t2 , v1, v2, v , t ;
	cout << "t1=";
	cin>> t1;
	cout << "t2=";
	cin>>t2;
	cout <<"v1=";
	cin >> v1;
	cout << "v2 =";
	cin >> v2;
	t = ((v1 + v2)*t2 + v1*t1)/(2*v1 + v2) ;
	cout <<" t = "<< t << endl;
	v = v1 + v2 ;
	cout << "v ="<< v ;
	return 0 ;
}

// Kubning qirrasi a uning yuzasi hamda hajmini topish dasturi
	
#include<iostream>

using namespace std ;

int main (){
	int a, V , S;
	cin>>a;
	V = a*a*a;
	cout << "V = "<< V << endl;
	S = 6*a*a ;
	cout << " S = "<<S;
	return 0;
}	
	
	//sonning bo'luvchilari yig'indisi
	//funksiya orqali
	
	int add(int a) {
	int s=0;
	for(int i = 1 ; i<a ; i++) {
		if(a%i==0)
			s+=i;
		
	}
	return s;
}
int main() {
	int a;
	cin>>a;
	cout<<add(a);
	return 0;
}
	
	
	
	
	/*natural sonning raqamlar
yig'indisifunksiya orqali*/


int add(int a  ) {
	int sum = 0 , b;
	while(a>0) {
		b=a%10;
		sum=sum+b;
		a=a/10;
	}
	return sum;
}
	int main() {
		int a;
		cin>>a;
		cout<<add(a);
	}


