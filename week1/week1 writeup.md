NOTES OF 229a 

#lec1
supervised learning -> is simply about geeting output for y given input x using labeled data
unsupervised learning -> is about finding structure in unlabeled data
reinforcement learning -> is when we are experimenting if we get a good result we store it and if we get a bad result we discard it

important things to check on internet
1 support vector machine -> infinite no of input variables(from lec see more about it)

#lec2
linear regression -> is a supervised learning algorithm that is used to predict a continuous value 
                    -> it is used to predict a value given a set of input variables
                    eq: e(x) = 1/n(summation from i=1 to n) (r^t-g(x^t))^2
                    -> r is the actual value and g(x) is the predicted value
                    -> n is the number of training examples
                    -> x is the input vector
                    -> square is because we want to minimize the error
<!-- todo! try a simple regression model based on a simple stock price for linear regression for one stock --> 
<!-- done-->

feature vector -> A feature vector is an ordered list of numerical properties of observed phenomena like the good and bad features of a column of our dataset table maybe not sure once verify
            -> its used in breast cancer identification using the equation f(x) = f(a) + f`(a)(x-a)/1! + f``(a)(x-a)^2/2!.... to identify the good features of the cancer cells and the bad features of the cancer cells since humans cant identify which are the best it kind of goes into deep learning catogery which i have to yet learn


gradient descent : https://medium.com/swlh/basics-and-beyond-gradient-descent-87fa964c31dd
