
// -------------------------------------- M. JAWAD KHAN
// --------------------------------------  ROLL NO (P19-0053)
// -------------------------------------  ASSIGMENT NO 2
// -------------------------------------  SECTION A

 
#include<iostream>
#include<string>
using namespace std;

void implication(string abc,string xyz)
{
    
	if(abc=="!p->q")
	{
	
	cout<<"The converse of the proposition is =    q->!p"<<endl;
	cout<<"The contrapositive of the proposition is =   !q->p"<<endl;
	cout<<"The inverse of the proposition is =          p->!q"<<endl; 
	
	cout << "___________________________________________________________________" << endl;
	}
	else if (abc=="p->!q")
	{
	cout<<"the converse of the proposition is =       !q->p"<<endl;
	cout<<"The contrapositive of the proposition is =   q->!p"<<endl;
	cout<<"The inverse of the proposition is =       !p->q"<<endl; 	
	
	cout <<"___________________________________________________________________________" << endl;
	}
	else if (abc=="p->q")
	{
	cout<<"the converse of the proposition is =        q->p"<<endl;
	cout<<"the contrapositive of the porposition is =     !q->!p"<<endl;
	cout<<"the inverse of the proposition  is =         !p->!q"<<endl;
	
	cout <<"______________________________________________________________________________"  << endl;	
	}
	else if(abc=="!p->!q")
	{
	cout<<"the converse of the proposition is =       !q->!p"<<endl;
	cout<<"the contrapositive of the proposition is =    q->p"<<endl;
	cout<<"the inverse of the proposition is =        p->q"<<endl;
	
	cout <<"__________________________________________________________________________________" << endl;
	}
	else
	{
		cout<<"SOORY ! your proposition is incorrect"<<endl;
	}
}

void contrapositive(string abc,string xyz)
{
	if(abc=="!p->q")
	{
	cout<<"the implication of the proposition is =   !q->p"<<endl;
	cout<<"the converse of the proposition is =     p->!q"<<endl;
	cout<<"the inverse of the proposition is =      q->!p"<<endl;
	
	cout <<"____________________________________________________________" << endl;
	}
	else if (abc=="p->!q")
	{
	cout<<"the implication of the proposition is =   q->!p"<<endl;
	cout<<"the converse of the proposition is =   !p->q"<<endl;
	cout<<"the inverse of the proposition  is =    !q->p"<<endl;
	
	cout <<"_____________________________________________________________________" << endl;
	}
	else if(abc=="p->q")
	{
	cout<<"the implication of the proposition is =   !q->!p"<<endl;
	cout<<"the converse of the proposition is =     !p->!q"<<endl;
	cout<<"the inverse of the proposition is =      q->q"<<endl;
	
	cout <<"_________________________________________________________________________" << endl;
	}
	else if(abc=="!p->!q")
	{
	cout<<"the implication of the proposition is =  q->p"<<endl;
	cout<<"the converse of the proposition is =    p->q "<<endl;
	cout<<"the inverse of the proposition is =    !q->!p"<<endl;
	
	cout <<"___________________________________________________________________________________" << endl;
	}
	else
	{
		cout<<"SOORY ! your proposition is incorrect"<<endl;
	}
	
}
void converse(string abc,string xyz)
{
	if(abc=="!p->q")
	{
	cout<<"the implication of the proposition  is =    q->!p"<<endl;
	cout<<"the contrapositive of the proposition is =   p->!q"<<endl;
	cout<<"the inverse of the proposition is =        !q->p"<<endl;
	
	cout <<"________________________________________________________________" << endl;
	}
	else if(abc=="p->!q")
	{	
	cout<<"the implication of the proposition is =    !q->p"<<endl;
	cout<<"the contrapositive of the proposition is =  !p->q"<<endl;
	cout<<"the inverse of the proposition is =         p->!q"<<endl;
	
	cout <<"_______________________________________________________________________" << endl;
	}
	else if(abc=="p->q")
	{
	cout<<"the implication of the proposition  is =     q->p"<<endl;
	cout<<"the contrapositive of the proposition is =  !p->!q"<<endl;
	cout<<"the inverse of the proposition is =          p->q"<<endl;
	
	cout <<"___________________________________________________________________________" << endl;
	}
	else if(abc=="!p->!q")
	{
	cout<<"the implication of the proposition is =    !q->!p"<<endl;
	cout<<"the contrapositive of the proposition is =  p->q"<<endl;
	cout<<"the inverse of the proposition  is =          q->p"<<endl;	
	
	cout <<"________________________________________________________________________________" << endl;
	}
	else
	{
		cout<<"SOORY ! your proposition is incorrect"<<endl;
	}
}

void inverse(string abc,string xyz)
{
	if(abc=="!p->q")
	{
	cout<<"the implication of the proposition is =   P->!q"<<endl;
	cout<<"the contrapositive of the proposition is = q->!p"<<endl;
	cout<<"the converse of the proposition is =        !q->p"<<endl;
	
	cout <<"________________________________________________________________________________________" << endl;
	}
	else if(abc=="p->!q")
	{
	cout<<"the implication of the proposition is =    !p->q"<<endl;
	cout<<"the contrapositive of the proposition  is =  !q->p"<<endl;
	cout<<"the converse of the proposition  is =        q->!p"<<endl;
	
	cout <<"__________________________________________________________________________" << endl;
	}
	else if(abc=="p->q")
	{
	cout<<"the implication of the proposition  is =    !p->!q"<<endl;
	cout<<"the contrapositive of the proposition  is =  q->p"<<endl;
	cout<<"the converse of the proposition is =       !q->!p"<<endl;	
	
	cout <<"_________________________________________________________________________" << endl;
	}
	else if(abc=="!p->!q")
	{
	cout<<"the implication of the proposition  is =     p->q"<<endl;
	cout<<"the contrapositive of the proposition  is =   !q->!p"<<endl;
	cout<<"the converse of the proposition  is =        q->p"<<endl;
	
	cout <<"_______________________________________________________________________________" << endl;
	}
	else
	{
		cout<<"SOORY ! your proposition is incorrect"<<endl;
	}
}




int main()
{
string abc;
string xyz;

char z='y';

while(z=='y')
{


cout<<"enter the value of proposition"<<endl;
cin>>abc;
cout<<"enter the form of proposition"<<endl;
cin>>xyz;
if(xyz=="implication")
{
implication(abc,xyz);
}
else if(xyz=="contrapositive")
{
	contrapositive(abc,xyz);
}
else if (xyz=="inverse")
{
	inverse(abc,xyz);
}
else if (xyz=="converse")
{
	converse(abc,xyz);
}
else
{
	cout<<"SOORY ! your proposition is incorrect"<<endl;
}
cout <<"If you want to check more proposition then plzz enter the (y)*** " << endl;
cout<<"press y to countinue"<<endl;
cin>>z;
}
system ("pause");
return 0;
}
