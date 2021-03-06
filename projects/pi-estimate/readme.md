# Estimating the value of Pi

Write a function that estimates the value of pi by the 'throw darts at a wall' method.  That is, generate random `(x,y)` points and see if they fall within the unit circle, and use these results to estimate pi.  

* Do this estimate using 100, 1000, 10,000, and 1e6 points.  (hint: check out the [timeit](https://docs.python.org/2/library/timeit.html) module to help with timing snippets of code.)
* How long does the calculation take for different numbers of points?  Make a figure that illustrates how the calculation time depends on the number of points.
* Make a figure that displays the "darts."
* Run this calculation many times for a single `N` (number of darts), and plot a histogram of the results.  What is the mean and standard deviation of these estimates?
* Make a plot that illustrates the precision of the pi estimate as a function of number of random points used.

Make a notebook that demonstrates how your code works, as well as presenting the results of all your calculations.  The notebook should have minimal complicated code in it; rather, it should initialize objects or call functions defined within a module you have written.
