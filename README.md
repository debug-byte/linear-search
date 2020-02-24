# linear-search
#include <iostream>

using namespace std;

int main()

{
	int a[45];
	int n;
	int i;
	int max;
	int min;
	
	cout << "Enter the size of the array :"<<endl;
	
	cin>>n;
	
	cout << "Enter the elements in the array :"<<endl;
	
	for(i=0;i<n;i++)
	
	cin>> a[i];
	
	max = a[0];
	
	for (i=0;i<n;i++)
	{
		if (max < a[i])
		
		max = a[i];
		
	}
	min = a[0];
	for (i=0;i<n;i++)
	{
		if (min > a[i])
		
		min = a[i];
		
		 
	}
	cout << "Largest element :"<< max <<endl;
	
	cout << "Smallest element :"<< min <<endl;
	
	return 0;
	
}
