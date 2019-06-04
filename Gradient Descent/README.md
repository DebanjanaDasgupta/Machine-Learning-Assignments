Consider the problem of gradient descent that was discussed in class - you would like to predict the
number of A grades that a student in the second year of the M.S. program receives (y) based on the
number of A grades that the student received in the rst year of the M.S. program (x). You propose
a hypothesis of the form h(x) = theta_0 + theta_1 * x, where theta_0 and theta_1 are parameters that you want to find. The
data is presented below:

x = {3,1,0,4} 
y = {2,2,1,3}


You start with an initial choice of parameters as: theta_0 = 0 and theta_1 = 1. You can assume that the error
function is: J = 1/2m Sum_i=1_to_m(h_theta(x^i) - y^i)^2
where m is the number of training examples. Run at most 5 rounds of the gradient descent algorithm
discussed in class. Does your error go down after 5 rounds? Show all the steps of your calculation.
