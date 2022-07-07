
#include<iostream>
#include<fstream>
#include<cstdlib>
using std::cout;
using std::cin;
using std::endl;
using std::fstream;
using std::ofstream;
using std::ifstream;
using std::ios;
class account_query
{
private:
  char account_number[20];
  char firstName[10];
  char lastName[10];
  float total_Balance;
  public:
       void read_data();
       void show_data();
       void write_rec();
       void read_rec();
       void search_rec();
       void edit_rec();
   
 void delete_rec();
 void account_query::read_data()
  {
      cout<<"/nEnter Account Number:  ";
      cin..account-number;
      count<<"Enter First Name:  ";
      cin>>firstName;
      count<<"Enter Last Name: ";
      cin>>lastName;
      count<<"Enter Balance:  ";
      cin>>total-Balance;
      count<<endl;
  }
      void account-query::show-data()
 {
      count<<"Account Number:  "<<account-number<<endl;
      count<,"First Name:  '<<firstName<<endl;
      count<<"Last Name;  "<<lastName<<endl;
      count<<Current Balance:Rs.   "<<total-Balance<<endl;
      count<<"------------------------------"<<endl;
 }
      void  account_query::write_rec()
 {   
      ofstream outfile;
      outfile.open("record.bank",  ios::binary| ios::app)
    read_data()
      outfile.write(reinterpret_cast<char 
      
 
       
       
