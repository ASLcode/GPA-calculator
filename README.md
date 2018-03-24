#include <iostream>
#include <vector>
using namespace std;

//will keep the course and grades in one
struct course{
  string name;
  double grade;
};

int main(){
  //will store the courses and grades
  vector <course> Courses(10);
  
  int courseNum;
  
  cout << "How many courses do you have? (Number must be less than 7) ";
  cin >> courseNum;
  
  //asking for user to input all their classes and the grades
  for(int i = 0; i <= courseNum - 1; i++){
    cout << "What is the name of the course? ";
    cin >> Courses.at(i).name;
    cout << "What about the grade? ";
    cin >> Courses.at(i).grade;
  };
  
  //will print after the input is complete
  cout << endl;
  cout << "Class input completed. "
  cout << endl;
  
  //will print all the classes and the grades that
  //the user input
  for(int i = 0; i <= CourseNum - 1; i++){
    cout << Courses.at(i).name;
    cout << endl;
    cout << Courses.at(i).grade;

  };

}
