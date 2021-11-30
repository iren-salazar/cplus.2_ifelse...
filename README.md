# cplus.2_ifelse...
determining whether its aperfect score or not.


#include <iostream>
using namespace std;
int main() {
    int grade;
    cout<<" Please enter grade: "<<endl;
    cin>>grade;
    
    if (grade==100)
    {
        cout<<" You've got a perfect score! "<<"\n";
    }else{
        cout<<" You didn't get a perfect score! "<<"\n";
    }
    return 0;
}
 /* output:
  
Please enter grade: 
100
You've got a perfect score!   */
  
  
