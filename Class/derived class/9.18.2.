#include <iostream> 
using namespace std; 
 
class BaseClass { 
public: 
  BaseClass() { cout << "Constructing base portion\n"; } 
  ~BaseClass() { cout << "Destructing base portion\n"; } 
}; 
 
class DerivedClass: public BaseClass { 
public: 
  DerivedClass() { cout << "Constructing derived portion\n"; } 
  ~DerivedClass() { cout << "Destructing derived portion\n"; } 
}; 
 
int main() 
{ 
  DerivedClass ob; 
 
  // do nothing but construct and destruct ob 
 
  return 0; 
}
