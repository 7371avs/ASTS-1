# ASTS-1
#include <iostream>
#include <cmath>
using namespace std;
 
int main()
{
    const double PI = 3.141592653589793238463;
    double a, z1, z2;
    cout <<"a="; 
    cin >>a;
    
    z1=2*(pow(sin(3*PI-2*a),2))*(pow(cos(5*PI+2*a),2));    
    z2=(1.0/4.0)-((1.0/4.0)*sin((5.0/2.0)*PI-(8*a)));
    
    cout <<"z1="<<z1<<"  z2="<<z2<<endl;
   
return 0;
}
