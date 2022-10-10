//# Reverse-Integer : This code takes an Integer and returns it with the numbers reversed



#include <iostream>

using namespace std;

int reverseDigit(int num){
  int revNum = 0;

  while(num != 0){
    revNum = revNum*10 + num%10;
    num = num / 10;
  }
  return revNum;
}


int main() {
    // Write your main here
    int num;
  cout<<"enter num"<<endl;
  cin>>num;

  cout<<"the value of is "<<reverseDigit(num)<<endl;


  return 0;

}


