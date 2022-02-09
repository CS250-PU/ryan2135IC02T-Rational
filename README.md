# CS250 Intro to CSII IC02 - Rational

**CS250 Intro to CSII\
Lab Practice on Classes**

**[Problem:]{.ul}** A rational number is defined to be any number that
can be expressed in the form p/q where p and q are each integers and q
is not equal to 0.

**[Task:]{.ul}** Create a C++ project to represent and use a rational
number.

In Visual Studio, create a new project named **Rational**. Then do the
following:

1.  Create a class called **Rational** with two private data members:
    mNumerator (representing p) and mDenominator (representing q).
    Further, create a constructor that accepts two ints (p and q) as
    parameters. Set the default values of these parameters to 0 and 1
    for p and q respectively. The class Rational is to be created in a
    header file named Rational.h.

2.  Implement the constructor for the class Rational in a file named
    Rational.cpp.

3.  Write a driver (main) in RationalDriver.cpp that creates two
    Rational objects where one is created using the default constructor
    and the other creates a Rational object representing the rational
    number 4 (p = 4, q = 1).

4.  Add a public print function to the **Rational** class that will
    print a Rational object in the form p/q. The print method is to
    accept an ostream object passed by reference. Print both rational
    numbers to the screen.

5.  In the driver, create Rational objects to represent 2/3 and 4/5 and
    then print out each object.

6.  Add a function **equals** to class Rational that returns true if
    both Rational objects are equal; otherwise, false is returned. Test
    your function.

7.  Add a function **multiply** to class Rational that multiplies two
    Rational objects and returns a Rational object.
