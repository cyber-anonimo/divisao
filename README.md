# divisao
#include <cstdio>
using namespace std;
int main (){
	
	int num1 = 0;
	
	cout << "digite um numero: ";
	  cin >> num1;
	
	if(num1 % 3 == 0 && num1 % 7 == 0){
		cout << num1 << "e divisivel por 3 e 7.";
	}else{
		cout << num1 << "nao e divisivel por 3 e 7.";
	}
  return 0;
}
