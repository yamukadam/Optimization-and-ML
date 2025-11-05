Built upon the code provided from the simple neural network implemented in the paper Deep Learning: An Introduction for Applied Mathematicians by Higham and Higham in order
to compare various optimization methods in deep learning.
In particular, the original code had implemented a stochastic gradient descent with a fixed learning rate.

I modified the code to add from a per-sample backtracking line search that satisfies the armijo condition, a full batch BFGS, and also various global optimizers such as 
differential evolution, dual annealing, and basin hopping + l-bfgs and compared it on a simple 10 sample toy dataset.

I also then compared the optimization methods on the Wisconsin Breast Cancer dataset in order measure performance on a more complex dataset.

I also wrote a second report paper exploring different optimization/learning rate options in TensorFlow and how that affects model accuracy and # of iterations for convergence which is titled TensorFlow_Exploration
