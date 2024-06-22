#hello world
//program to compute co curricular activities for new students
#include <iostream>
#include <string>
#include <vector>

using namespace std;

struct student{
  string firstname;
  string surname;
  string gender;
  int age;
  string bbit group;
  string sport;
  vector<string>clubs;
}

vector<Student>students;
vector<string>sport={"Rugby","Athletics","Swimming","Soccer"};
vector<string>club={"Journalism","Red Cross Society","AISEC","Business Club","Computer Science Club"};

void add student(){
 Student student;
 cout<<"Enter students first name:";
 cin>>student firstname;

 cout<<"Enter students surname:";
 cin>>student surname;

 cout<<"Enter students gender:";
 cin>>student gender;

 cout<<"Enter student age:";
 cin>>student age;

 cout<<"Enter student BBIT group:";
 cin>>student bbit group;

 //select sport
 if(student gender=="Male"||student gender=="Female"){
   cout<<"Select a sport from the following options:\n";
   for(int i=0;i<sport size;i++){
     cout<<i+1<<"."<<sports[i]<<endl;
     }
     int choice;
     cin>>choice;
     student sport=sports[choice-1];
  }
