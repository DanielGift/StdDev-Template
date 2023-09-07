# StdDev-Template
On GitHub, there is an outline of the code you will need to write. It includes 4 methods (plus the main method):
avg, which takes in 3 ints and returns the average 
var, which takes in 3 ints and returns the variance. It should call avg.
stdDev, which takes in 3 ints and returns the standard deviation. It should call var.

Fill out each method so that it does what it claims. Don’t forget a return, and a Function Comment before each method describing what it does. Be sure to also include a Class Comment describing what the whole class does.

You should include 2 tests of your code. The first should be of the numbers 78, 80, and 77. With these starting numbers, your printed output should be exactly the following:

For the numbers 78, 80, 77

The Average is 78.33333333333333

The Variance is 1.5555555555555556

The Standard Deviation is 1.247219128924647

Your other test should use different numbers but should follow this exact format as well. You are welcome to include more tests in addition.
Make sure that your tests include comments that explain what you expect the output of that test to be.


**Math background:**
Let {a1, a2, a3, …, an} be a set of n real numbers

The average of the list is ave = (a1+a2+…an)/n
The variance of the list is [(a1-ave)2 + (a2-ave)2 + … + [(an-ave)2]/n
The standard deviation is the square root of the variance
Hint: to get a square root of x, use Math.sqrt(x)

 
