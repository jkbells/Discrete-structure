#include <iostream>

using namespace std;

void reflexive(int a[], int sizeOfA, int b[], int sizeOfB)
{
	int i, j;
	bool test;
	bool hold = true;

	for(i = 0; i < sizeOfA; i++)
	{
		if(hold == true)
		{
			for(j = 0; j < sizeOfB;)
			{
				if(b[j] == a[i])
				{
					hold = true;
					break;
				}
				else
				{
					hold = false;
					cout << "Reflexive - No" << endl;
					break;
				}
			}
		}
	}
	if(hold == true)
	{
		test = true;
		cout << "Reflextive - Yes" << endl;
	}
}

void charReflexive(char a[], int sizeOfA, char b[], int sizeOfB)
{
	int i, j;
	bool test;
	bool hold = true;

	for(i = 0; i < sizeOfA; i++)
	{
		if(hold == true)
		{
			for(j = 0; j < sizeOfB;)
			{
				if(b[j]==a[i])
				{
					hold = true;
					break;
				}
				else
				{
					hold = false;
					cout << "Reflexive - No" << endl;
					break;
				}
			}
		}
	}
	if(hold == true)
	{
		test = true;
		cout << "Reflextive - Yes" << endl;
	}
}

void symmetric(int a[], int sizeOfA, int b[], int sizeOfB)
{
	int i, j;
	bool test;
	bool hold = true;

	for(i = 0; i < sizeOfA; i++)
	{
		if(hold == true)
		{
			for(j = 0; j < sizeOfB;)
			{
				if(a[i] == a[j] && a[i+1] == a[j-1])
				{
					hold = true;
					break;
				}
				else
				{
					hold = false;
					cout << "Symmetric - No" << endl;
					break;
				}
			}
		}
	}
	if(hold == true)
	{
		test = true;
		cout << "Symmetric - Yes" << endl;
	}
}

void charSymmetric(char a[], int sizeOfA, char b[], int sizeOfB)
{
	int i, j;
	bool test;
	bool hold = true;

	for(i = 0; i < sizeOfA; i++)
	{
		if(hold == true)
		{
			for(j = 0; j < sizeOfB;)
			{
				if(a[i] == a[j] && a[i+1] == a[j-1])
				{
					hold = true;
					break;
				}
				else
				{
					hold = false;
					cout << "Symmetric - No" << endl;
					break;
				}
			}
		}
	}
	if(hold == true)
	{
		test = true;
		cout << "Symmetric - Yes" << endl;
	}
}

void antiSymmetric(int a[], int sizeOfA, int b[], int sizeOfB)
{
	int i, j;
	bool test;
	bool hold = true;

	for(i = 0; i < sizeOfA; i++)
	{
		if(hold == true)
		{
			for(j = 0; j < sizeOfB;)
			{
				if(a[i] <= b[j] && b[j] <= a[i])
				{
					hold = true;
					break;
				}
				else
				{
					hold = false;
					cout << "Antisymmetric - No" << endl;
					break;
				}
			}
		}
	}
	if(hold == true)
	{
		test = true;
		cout << "Antisymmetric - Yes" << endl;
	}
}

void charAntiSymmetric(char a[], int sizeOfA, char b[], int sizeOfB)
{
	int i, j;
	bool test;
	bool hold = true;

	for(i = 0; i < sizeOfA; i++)
	{
		if(hold == true)
		{
			for(j = 0; j < sizeOfB;)
			{
				if(a[i] <= b[j] && b[j] <= a[i])
				{
					hold = true;
					break;
				}
				else
				{
					hold = false;
					cout << "Antisymmetric - No" << endl;
					break;
				}
			}
		}
	}
	if(hold == true)
	{
		test = true;
		cout << "AntiSymmetric - Yes" << endl;
	}
}

void transitive(int a[], int sizeOfA, int b[], int sizeOfB)
{

}

void charTransitive(char a[], int sizeOfA, char b[], int sizeOfB)
{

}


int main()
{
	char keepGoing = 'y';
    while (keepGoing=='y') {


	int set1[6] = {1, 2, 3, 4, 5, 6,};
	int rel1[14] = {1,1,2,2,3,2,3,3,4,4,5,5,6,6};
	cout<<"Set 1"<<endl;
	reflexive(set1, 6, rel1, 14);
	symmetric(set1, 6, rel1, 14);
	antiSymmetric(set1, 6, rel1, 14);


	int set2[6] = {1, 2, 3, 4, 5, 6,};
	int rel2[16] = {1,1,2,2,3,2,2,3,3,3,4,4,5,5,6,6};
	cout<<"Set 2"<<endl;
	reflexive(set2, 6, rel2, 16);
	symmetric(set2, 6, rel2, 16);
	antiSymmetric(set2, 6, rel2, 16);


	int set3[6] = {1, 2, 3, 4, 5, 6,};
	int rel3[4] = {1,1,2,2};
	cout<<"Set 3"<<endl;
	reflexive(set3, 6, rel3, 4);
	symmetric(set3, 6, rel3, 4);
	antiSymmetric(set3, 6, rel3, 4);


	int set4[] = {};
	int rel4[4] = {};
	cout<<"Set 4"<<endl;
	reflexive(set4,0 , rel4, 0);
	symmetric(set4,0, rel4,0 );
	antiSymmetric(set4,0 , rel4,0 );



	cout << endl << "Would you like to test it again? (y/n): ";
    cin >> keepGoing;
	}

	return 0;
}

