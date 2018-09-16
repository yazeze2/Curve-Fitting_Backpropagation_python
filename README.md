# CurveFitting_Backpropagation_python
Sinusoidal Function Curve fitting

In this project the backpropagation algorithm was used to fit a given sinusoidal function. The algorithm was implemented through online learning to find the optimal weights that minimize the mean squared error. The gradient change from one epoch the next was monitored to detect convergence. (when the gradient change is detected to insignificantlychange from one epoch to the other, it was deduced the algorithm succesfully reached a global or local minimu; hence convergence) Also, the MSE in each epoch was tracked to confirm the algorithm is performing its target task, which is minimizing the MSE as low as possible. The following are the given sinusoidal function, the MSE progress over Epoch and finally, the fit from the algorithm. As it can be seen, the BPN algorithm nicely fits the given function.

![image](https://user-images.githubusercontent.com/32316270/45592970-f25c9780-b940-11e8-8390-68a6e8ac0c66.png)

![image](https://user-images.githubusercontent.com/32316270/45592990-3b145080-b941-11e8-92d1-84fb791be6b6.png)

![image](https://user-images.githubusercontent.com/32316270/45593005-8e869e80-b941-11e8-916f-d9156411fe4c.png)

