java c
AM2060 Assignment 2024
1    Introduction
You are to implement Gaussian elimination to solve systems of linear equations in C#.
2    Speciﬁc requirements
1.  Create a class called GaussEliminate which implements the algorithm. Your code must include the following methods:
(a) void SetAb(double [,] A, double [] b); //allows the user to specify the problem to be solved.
(b) double  []  Solve();  //solves  the  problem,  outputs  the  formatted  answer  to screen and returns the answer to an array.
(c) void DisplayAugMatrix(); //outputs the Augmented matrix to the screen in an easy to read and well formatted way.
(d) Implement partial pivoting and scaled partial pivoting (see the notes on can- vas).   Can  you think of a way to  allow the user to choose the method of solution i.e. no pivoting, partial pivoting or scaled partial pivoting?
(e) Your code should be able to deal with a zero in the piv代 写AM2060 Assignment 2024SPSS
代做程序编程语言ot position.
(f) Your code should work for systems of equations of dimension 2 or higher.
2.  Try to deal with all potential errors e.g.  making sure matrices and vectors are correctly sized.
3.  Keep your code tidy and readable.  Put in a reasonable amount of comments but no essays. Comments should help the reader understand your code.
4. I will test your code by running code like the following against it:
GaussEliminate g = new GaussEliminate();
double [,] A1= new double[4,4]{{10,1,1,1},{1,1,2,3},{-1,1,2,1},{3,2,-1,0}};
double [] b1 = new double[4] {1,2,-10,1};
g.SetAb(A1,b1);
g.Solve();
double [,] A2= new double[3,3]{{5,1,2},{-3,9,4},{1,2,-7}};
double [] b2 = new double[3] {10,-14,-33};
g.SetAb(A2,b2);
g.Solve();
5. You are only required to submit the ﬁle containing the code for the GaussEliminate class, i.e. a code ﬁle ending in .cs.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
