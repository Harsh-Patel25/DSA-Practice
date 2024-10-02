#include <bits/stdc++.h>
using namespace std;

void print1(int n)
{
	for(int i=1; i<n; i++)
	{
		// number
		for(int j=1; j<=i; j++)
		{
			cout<<j;
		}
		//space
		for(int j=1; j<=((2*n)-(2*i)); j++)
		{
			cout<<" ";
		}
		//number
		for(int j=i; j>=1; j--)
		{
			cout<<j;
		}
		cout<<endl;
	}
}

void print2(int n)
{
	int sum=1;
	for(int i=1; i<=n; i++)
	{
		for(int j=1; j<=i; j++)
		{
			cout<<sum<<" ";
			sum++;
		}
		cout<<endl;
	}
}

void print3(int n)
{
	for(int i=0; i<n; i++)
	{
		for(char ch='A'; ch<='A'+(n-i-1); ch++)
		{
			cout<<ch<<" ";
		}
		cout<<endl;

	}
}

void print4(int n)
{
	for(int i=0; i<n; i++)
	{
		char ch;
		for( int j=n; j>i; j--)
		{
			ch='A'+n-j;
			cout<<ch<<" ";

		}

		cout<<endl;
	}

}

void print5(int n)
{
	for(int i=0; i<n; i++)
	{
		char ch;
		for(int j=n; j>i; j--)
		{
			ch='A'+i;
			cout<<ch<<" ";

		}

		cout<<endl;
	}

}

void print6(int n)
{
	for(int i=0; i<n; i++)
	{
		//space
		for(int j=0; j<n-i-1; j++)
		{
			cout<<" ";
		}
		//character
		char ch='A'-1;
		for(int j=0; j<2*i+1; j++)
		{
		    if(j<=i){
		        
			ch++;
		    }
			else//if(j>i)
			{
				ch--;
			}
			cout<<ch;
		}
		//space
		for(int j=0; j<n-i-1; j++)
		{
			cout<<" ";
		}
		cout<<endl;
	}
}

void print7(int n)
{
    for(int i=0;i<n;i++)
    { char ch;
            ch='A'+n-i-1;
        for(int j=0;j<=i;j++)
        {
            cout<<ch;
            ch++;
        }
        cout<<endl;
    }
}

void print8(int n)
{
	for(int i=0; i<n-1; i++)
	{
		
		for(int j=0; j<n-i-1; j++)
		{
			cout<<"*";
		}
		
		if(i>-1) {cout<<" ";}
		
		for(int j=0; j<2*i+1; j++)
		{
		    cout<<" ";
		}
		
		for(int j=0; j<n-i-1; j++)
		{
			cout<<"*";
		}
		cout<<endl;
	}
}

void print9(int n)
{
	for(int i=1; i<=n; i++)
	{
		for(int j=0; j<i; j++)
		{
			cout<<"*";
		}
		
			if(i<n) {cout<<" ";}
		
		for(int j=0; j<2*n -(2*i +1); j++)
		{
		    cout<<" ";
		}
		for(int j=0; j<i; j++)
		{
			cout<<"*";
		}
		cout<<endl;
	}
}
// print 8 and 9 no or che.
// #include <iostream>
// using namespace std;

// void print8(int n) {
//     // Upper half of the diamond
//     for (int i = 0; i < n; i++) {
//         // Print left stars
//         for (int j = 0; j < n - i; j++) {
//             cout << "*";
//         }

//         // Print spaces
//         for (int j = 0; j < 2 * i; j++) {
//             cout << " ";
//         }

//         // Print right stars
//         for (int j = 0; j < n - i; j++) {
//             cout << "*";
//         }
//         cout << endl; // Move to the next line
//     }
// }

// void print9(int n) {
//     // Lower half of the diamond
//     for (int i = 0; i < n; i++) {
//         // Print left stars
//         for (int j = 0; j < i + 1; j++) {
//             cout << "*";
//         }

//         // Print spaces
//         for (int j = 0; j < 2 * (n - i - 1); j++) {
//             cout << " ";
//         }

//         // Print right stars
//         for (int j = 0; j < i + 1; j++) {
//             cout << "*";
//         }
//         cout << endl; // Move to the next line
//     }
// }





int main()
{
	int n;
	cin>>n;
	print9(n);
	print8(n);
	cout<<endl;
	print8(n);
	print9(n);
}