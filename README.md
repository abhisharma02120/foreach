// foreach
#include <iostream>
#include <vector>
using namespace std;
 
int main() {
 
      vector<string> value{"This", "is", "foreach", "example", "using", "vector."};
     
    cout<<"Traversing the vector with foreach using vector's data type: ";
    for (string v : value) {
        cout<<v<<" ";
    }
 
    cout<<"\nTraversing the vector with foreach using auto keyword      : ";
      for (auto v : value)
      cout<<v<<" ";
    return 0;
}
