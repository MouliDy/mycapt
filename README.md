#include<iostream>
using namespace std;
 
int main()
{
    cout << "Size of char : " << sizeof(char)
      << " byte" << endl;
    cout << "Size of int : " << sizeof(int)
      << " bytes" << endl;
    cout << "Size of float : " << sizeof(float)
       << " bytes" <<endl;
    cout << "Size of double : " << sizeof(double)
       << " bytes" << endl;
    return 0;
}

#include<iostream>
using namespace std;
 
int main()
{
    float a,b;
    cout << "Enter two numbers : ";
    cin >> a;
    cin >> b;
    cout << "Product = " << (a*b);
    return 0;
}
