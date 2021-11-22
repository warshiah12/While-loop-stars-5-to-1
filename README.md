# While-loop-stars-5-to-1
falling stars
#include<iostream>
using namespace std;
int main()
{
	int j, z = 1;
	j = 1;
	while (j <= 5)
	{
		z = j;
		while (z <= 5)
		{
			z++;
			cout << "*";
		}
		j++;
		cout << endl;
	}
	return 0;
}
