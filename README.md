# Intermediate-PA1

This program takes in user inputs that create 3 points on a 3-D plane which form a triangle.
The triangle's area is then calculated using Heron's Formula. 

// A 3-dimensional point class!
// Coordinates are double-precision floating point.
class Point {

private:
double x;
double y;
double z;

public:
// Constructors
Point();                      // default constructor
Point(double x, double y);    // two-argument constructor

// Destructor
~Point();

// Mutator methods
void setX(double newX);
void setY(double newY);
void setZ(double newZ);

// Accessor methods
double getX();
double getY();
double getZ();
};
