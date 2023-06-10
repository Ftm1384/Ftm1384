- 👋 Hi, I’m @Ftm1384
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ftm1384/Ftm1384 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

The source code of the class project#include<iostream>
#include<string>
#include<fstream>
using namespace std;
class basic
{
	friend void chekstudent(int);
	friend void chekteacher(string);
	friend void chekclas(int);
	private:
		int id,cap;
		static int count;//Student count
		string teacher,dars,student;
		int n;
		float s,e;
		char week[5];
		bool q;
	public:
		besic(float start,float  end)
		{
			if(8>s||18>e)
			cout<<"erorr";
			s=start;
			e=end;
		}
		void get()
		{
			cout<<"enter dars:";
			cin>>dars;
			cout<<"enter capacity:";
			cin>>cap;
			cout<<"enter familyname teacher:";
			cin>>teacher;
	    	string teacher;
	    	cout<<"enter teacher:";
	    	cin>>teacher;
			cout<<"enter days week:";
			cin.getline(week,5);
			cout<<"by sistem?";
			cin>>q;
			if(q==true)
			{
		    void chek(int id)
		    {
		        {
			       for(id;i==true;id++)
			       {
				     cout<<"erorr(for similary class)";
			        }
		        }
		        if(count!=(fstream clasha))
		        	cout<<"erorr(capacity)";
			}
			    else
			    {	
			    cout<<"enter number class(id):";
			    cin>>id;
			    }
		    }
};
void chekstudent(int student)
{
	if(count<40)
	{
	cout<<"enter number student:";
	cin>>student;
	count++;
	fstream sstudent;
	{sstudent.open("sstudent.dat",ios::out);
	int i=1;
	while(i<=40)
	{
	sstudent>>student;
	string st;
	st=student;
	}
    while(student!=st)
    {
	sstudent.open("liststudent.dat",ios::in|ios::app);
	sstudent<<student;
	}
	}
    }
}

void chekteacher(string teacher)
{
	for(id;teacher==t;id++)
	{
		cout<<"erorr(for somilary teacher";
	}
	fstream sstudent;
	{sstudent.open("sstudent.dat",ios::out);
    while(student!=st)
    {
	sstudent.open("liststudent.dat",ios::in|ios::app);
	sstudent<<teacher;
	}
}

void chekclas(int)
{
  for(id;i==true;id++)
  {
	cout<<"erorr(tadakhol class)";
	  }
 fstream clasha;
 clasha.open("clasha.txt",ios::in|ios::app);
 {
	clasha>>dars;
	clasha>>cap;
	clasha>>teacher;
 }
}

class addition:public basic
{
	private:
		int m,y,d,n,y1,m1,d1;
	public:
		addition(int year,int mon,int day)
		{
			if(m1>=6&&d1>32)
			cout<<"erorr";
			 if(m1>=12&&d1>31)
			 cout<<"erorr";
			y1=year;
			m1=mon;
			d1=day;
		}
		void get1()
		{
			cout<<"number of class session:";
			cin>>n;
		}
	    void end(int number,int year,int mon,int day)
		{
			for(int i=1;i<=n;i++)
			{
			d+=7;
			if(m>=6&&d>32)
			{
				++m;
				d-=31;
			}
			if(6>m<12&&d>31)
			{
				++m;
				d-=30;
			}
			if(m==12&&d>30)
			{
				y++;
				m=1;
				d-=29;
			}
		    }
			n=number;
			y=year;
			m=mon;
			d=day;
		}
};

int main()
{
	float start, end;
	int year, mon, day;
	cout<<"start time"<<"end time";
	cin>>start>>end;
	cout<<"start:"<<"year"<<"mon"<<"day";
	cin>>year>>mon>>day;
	basic ob1;
	ob1.get();
	cout<<endel;
	chekstudent(student);
	chekteacher(teacher);
	chekclas(id);
	cout<<"---------------------------------"<<endel;
	addition ob2;
	ob2.get1();
	ob2.end();
	ob2.get();
	cout<<"----------------------------------";
	return 0;
}
