# SmartPointers

Create a program that has the following:

1. a function named make that creates and returns a unique_ptr to a vector of shared_ptrs to Test objects. 

2. a function named fill that expects a vector of shared pointers to Test objects and a int
   representing the number of Test objects to create dynamically and add to the vector.
   
   This function will prompt the user to enter an integer, create a shared_ptr to a Test object 
   initialized to the entered integer and add that shared pointer to the vector.
   
3. a function named display that expects a vector of shared_ptrs to Test object and displays the
   data in each Test object

    
Below is a sample run for the user entering 3 at the console:
    
How many data points do you want to enter: 3

Enter data point [1] : 10
        Test constructor (10)

Enter data point [2] : 20
        Test constructor (20)

Enter data point [3] : 30
        Test constructor (30)

Displaying vector data
=======================
10
20
30
=======================
        Test destructor (10)
        Test destructor (20)
        Test destructor (30)
