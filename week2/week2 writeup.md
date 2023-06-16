cost function -> we square the distances between the predicted and actual values or we can do absolute value of the difference between the predicted and actual values because to cancel the negative distances and we send this trhough a gradient descent algo which predicts the values


see stochasitic gradient descent vs batch gradient descent once again 
but the one thing i understood from cs229a is stochastic gd is much faster compared to batch so like if u have 1000s of rows then batch gd is fine but if u have very large dataset then u need to use stochastic gd

batch gd caluculates the gradient for the entire dataset and then updates the parameters
stochastic gd calculates the gradient for one mini batch and then updates the parameters


gradient descent cs229 notes:
start with a random theta (vector) 
repeat until convergence:
    theta = theta - alpha * cost function gradient
    where alpha is the learning rate

in stochastic gradient descent we go from i to n and
take derivative of cost function wrt theta and update theta
the thing is in stochastic gradient descent i think we still iterate from 1 to n and not like take a random sample of the dataset but we compare it to precious and do and we dont caluculate power square thats why its faster ig not sure

j(theta) = 1/2[sigma iton (h(theta) - y)^2]
