/******************************************************************************

                              Online C++ Compiler.
               Code, Compile, Run and Debug C++ program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <iostream>
#include <vector>
using namespace std;


int main()
{
  /*
    Here we can verify several things:
        1) The memory of the entire vector cannot be utilized with pointer
           arithmetic to access array elements
           
        2) Just like Arrays, only a reference (such as the first element) to a
           vector element can be modified with pointer arithmetic to access other
           values.
           
           vector<int> *ptr = new vector<int>{1,8,3,4};
           int *intP = &(*ptr)[0];
           cout << *(intP+1);
  */
  
}
