# ransac
A simple RANSAC algorithm for fitting a 2D line

I created this simple serial program to give it as an assigment for my students to parallelize. The description is as follows:


Random Sample Consesus (RANSAC) is a classic technique in big data analysis. It is an iterative method to estimate the parameters of a model which fits a ``significant" number of observations in a given dataset. The observations which fit into the model are known as \textit{inliers} and the observations which do not fit are known as \textit{outliers}. Note that this approach is different from other commonly used parameter estimation techniques such as least squares which try to estimate a model which best fits all the data points. 

In this problem, we will implement a simple pthreads based RANSAC algorithm to fit a 2D line ($y = mx + c$, $m$ and $c$ are our model parameters) to fit a set of data points of the form $(x_i, y_i)$.

Compile:
gcc -o ransac ransac.c

run:
./ransac
