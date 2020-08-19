# Curve Fitting_Backpropagation_python
Sinusoidal Function Curve fitting

In this project the backpropagation algorithm was used to fit a given sinusoidal function (y = sin(20x) + 3x + v). The algorithm was implemented through online learning to find the optimal weights that minimize the mean squared error. The gradient change from one epoch to the next was monitored to detect convergence. (when the gradient change is detected to insignificantlychange from one epoch to the other, it was deduced the algorithm succesfully reached a global or local minima) Also, the MSE in each epoch was tracked to confirm the algorithm is performing its target task, which is minimizing the MSE as low as possible. The following are the given sinusoidal function, the MSE progress over Epoch and finally, the fit from the algorithm. As it can be seen, the BPN algorithm nicely fits the given function.

![image](https://user-images.githubusercontent.com/32316270/45593037-74998b80-b942-11e8-9dae-0799d18a2201.png)

![image](https://user-images.githubusercontent.com/32316270/45593047-8bd87900-b942-11e8-9859-538cd0842407.png)

![image](https://user-images.githubusercontent.com/32316270/45593048-972ba480-b942-11e8-9cee-0c1fbae4be34.png)
