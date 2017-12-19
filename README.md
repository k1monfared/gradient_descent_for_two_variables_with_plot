# gradient_descent_for_two_variables_with_plot

This uses the gradient descent to optimize the cost function for a regression line for two variables.
It plots the points given, line of regression, and the vertical error lines
It alos prints the equation of the line, as well as the number of iterations, and the final cost function value.
The outputs are the slope of the regression line and its y-intercept, respectively.

Here is a sample output:

    m,b = gradient_descent_for_two_variables([1,2,3],[3,5,5])
![m,b = gradient_descent_for_two_variables([1,2,3],[3,5,5])](https://github.com/k1monfared/gradient_descent_for_two_variables_with_plot/blob/master/sage0.png)

    The process converged in 34 iterations, and with a cost function value 
    of 0.000763885111059.
    The regression line is y = 1.42595071091 x + 0.703141606754.
And here is another one:

    X = [1,2,3,4,5,6,7,8,9,10]
    Y = [10,12,15,17,16,19,20,25,24,27]
    m,b = gradient_descent_for_two_variables(X,Y)
![X = [1,2,3,4,5,6,7,8,9,10];
Y = [10,12,15,17,16,19,20,25,24,27];
m,b = gradient_descent_for_two_variables(X,Y)](https://github.com/k1monfared/gradient_descent_for_two_variables_with_plot/blob/master/sage1.png)

    The process converged in 945 iterations, and with a cost function value
    of 0.000992275463616.
    The regression line is y = 1.97185757925 x + 7.42127711952.
