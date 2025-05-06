#include <iostream>
using namespace std;
class Number {;
public:
 int num_1;
 int num_2;
 int result;
 void res(){
  cin >> num_1;
  result = num_1 + 1;
  cout << " Следущее за число: " << result << " число: "<< endl;
  num_2 = result + 1;
  cout <<" Для числа: " << num_1 <<" Предыдущие число: "<< num_2 << endl;
 }
};
 int main()
 {
  setlocale(LC_ALL, "Russian");
  Number num;
  num.res();
  
 }
