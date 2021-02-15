#include <cmath>
#include <iostream>
using namespace std;

// define the structures
struct DataStructure
{
  float radius;
  double angle;
};

struct ResultStructure
{
  float area;
  double sine;
  double cosine;
  double tangent;
};

ResultStructure compute(struct DataStructure mystruct);

int main ()
{
    DataStructure input;
       ResultStructure output;

       input.radius = 3;

       input.angle = 0.8;

       output = compute(input);

    cout << " The area is "<< output.area << "\n";
       cout << " The sine of the angle is " << output.sine << "\n";
       cout << " The cosine of the angle is " << output.cosine << "\n";
    cout << " The tangent of the angle is " << output.tangent << "\n";
       return 0;
}

ResultStructure compute(struct DataStructure mystruct)
{
     ResultStructure answer;

        answer.area = pow(mystruct.radius,2);
        answer.sine = sin(mystruct.angle);
        answer.cosine = cos(mystruct.angle);
        answer.tangent = tan(mystruct.angle);

        return answer;
};
