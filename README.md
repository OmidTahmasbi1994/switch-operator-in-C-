# a-simple-example-for-the-switch-operator-in-C-


#include <iostream>
#include <conio.h>

using namespace std;
int main()

{
	int score;
	
	cout<<"Enter Your Test Score:"<<endl;
	cin>>score;
	
	switch (score/10)
	{
		case 10:
		case 9: cout<<"your grade is an A"<<endl; break;
		case 8: cout<<"your grade is a B"<<endl; break;
		case 7: cout<<"your grade is a C"<<endl; break;
		case 6: cout<<"your grade is a D"<<endl; break;
		case 5:
		case 4:
		case 3:
		case 2:
		case 1:
		case 0: cout<<"your grade is a F"<<endl; break;
		default: cout<<"Error: Score Is Out Of Range !"<<endl;	
	}
cout<<"<<<<< Goodbye >>>>>"<<endl;

getch();
}
