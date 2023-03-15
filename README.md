#include <iostream>  
#include<iomanip>  
using namespace std;
int main()
{
    int a;
    double b;
    cin >> a;
    b = a * 1.6;
    cout << fixed << setprecision(1) << b << endl;
    return 0;
}
你傳送了
3
你傳送了
#include <iostream>  
#include <math.h>  
  
using namespace std;  
int main()  
{  
    double x, y;  
    cin >> x >> y;  
    double d = x * x + y * y;  
    if (pow(d, 0.5) <= 100)  
    {  
        cout << "inside" << endl;  
    }  
    else {  
        cout << "outside" << endl;  
    }  
    return 0;  
}
你傳送了
4
你傳送了
#include<iostream>
using namespace std;
int main() {
	int inh, inm, outh, outm;
	cin >> inh >> inm;
	cin >> outh >> outm;

	int ttime = ((outh * 60) + outm) - ((inh * 60) + inm);

	if (ttime <=120 && ttime > 0)
	{
		cout << ttime / 30 * 30 << endl;
	}
	else if (ttime > 120 && ttime < 240 )
	{
		cout << (ttime-120) / 30 * 40 + 120<<endl;
	}
	else
	{
		cout << (ttime - 240) / 30 * 60 + 280 << endl;;
	}
}
