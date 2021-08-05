#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t;
	
	cin >> t;
	
	while(t--)
	{
	    float bs,hra,da,gs;
	    
	    cin >> bs;
	    
	    if(bs < 1500)
	    {
	        hra = 0.1*bs;
	        da = 0.9*bs;
	    }
	    else
	    {
	        hra = 500;
	        da = 0.98*bs;
	    }
	    
	    gs = bs + hra + da;
	    
	    printf("%.2lf\n",gs);
	    
	}
	return 0;
}
