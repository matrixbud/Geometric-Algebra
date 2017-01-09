# Geometric-Algebra Mathematica Package

This Geometric Algebra (GA) package was developed in January, 2017 using Mathematica 10 and performs GA operations in n-dimensions for any n. The package has been designed for Clifford algebras but can be configured to perform basic Grassmann algebra operations as well. All the commands work with either numbers and symbols. Thus, general formulas can be developed and identities can be checked. 

The package uses standard Mathematica notation. The user is not required to use special methods for keying input. For example, in 4-dimensional space-time, a basis would be e1, e2, e2, e4 and a vector (1,2,3,4) would be written as e1 + 2 e2 + 3 e3 + 4 e4 with the convention that e1 is the time axis. A palette is provided that allows the user to choose whether e12 = + 1 with ek2 = -1 for k > 1 or the opposite, e12 = -1 with ek2 = +1 for k > 1. The palette also allows the user to choose either Clifford or Grassmann algebra and, if Clifford, whether space or space-time.

Currently the package performs the following operations (all visible and easily entered from the palette):

•	Geometric product
•	Wedge product (with allowance for multivectors that span multiple grades)
•	Dot product (with allowance for multivectors that span multiple grades)
•	Left contraction (haven’t gotten around to right contraction yet)
•	Hodge Dual (provides 2 different ones found in current literature)
•	Inverse
•	Reverse
•	Norm
•	Gorm

The palette also simplifies typing of subscripted multivectors by providing a number of expression at the click of the mouse. If the desired expression is not there it may be more quickly entered by modifying one of the palette items than typing it in from scratch. The palette also allows the user to enter the symbols for the various products with mouse clicks.

The author welcomes collaboration. The package has not been beta tested so feedback on errors or quirks would be welcome. In particular, Mathematica 10 introduced a complication involving shadowing errors and the author has made an effort to prevent such errors from popping up. Still, there are certain errors a user can make to invoke these errors but hopefully they are quickly remedied by following the instructions in the Documentation. 
