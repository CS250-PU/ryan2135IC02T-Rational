# CS250 Intro to [CSII IC02 - Rational]

**CS250 Intro to CSII\
Practice on Classes**

<b>Problem:</b> A rational number is defined to be any number that
can be expressed in the form p/q where p and q are each integers and q
is not equal to 0.

<b>Task: </b> In Visual Studio, a solution named **Rational** exists.
You are to write code as follows:

1.  Create a class called **Rational** that has two private data members:
    mNumerator (representing p) and mDenominator (representing q).
    Further, create a constructor that accepts two ints (p and q) as
    parameters. Set the default values of these parameters to 0 and 1
    for p and q respectively. The class Rational is to be created in a
    header file named **Rational.h** that exists in the folder Header Files
    of the Visual Studio solution.

2.  Implement the constructor for the class Rational in a file named
    **Rational.cpp** which is to exists in the Source Files folder.

3.  Write a driver (main) in **RationalDriver.cpp** that creates two
    Rational objects where one is created using the default constructor
    and the other creates a Rational object representing the rational
    number 4 (p = 4, q = 1).

4.  Add a public **write** function to the Rational class that will
    write a Rational object in the form p/q to an output stream. The write function is to
    accept an ostream object passed by reference. 

5.  In the driver, create Rational objects to represent 2/3 and 4/5 and
    then print out each object.

6.  Add a function **equals** to class Rational that returns true if
    both Rational objects are equal; otherwise, false is returned. Write
    code in the driver to test your function.

7.  Add a function **multiply** to class Rational that multiplies two
    Rational objects and returns a Rational object.
