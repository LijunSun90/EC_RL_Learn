## Classical algorithms in RL

> Trust Region Policy Optimization (TRPO)

> Q-learning

> polucy gradient methods

> action-value methods

Methods for estimating the values of actions and for using the estimates to make action selection decisions.

> sample-average method for estimating action values

Each estimate action value is an average of the sample of observed rewards.

> neasr-greedy action selection rule or \epsilon-greedy method

Behave greedily most of the time, but with a small probability \epsilon, select randomly from among all the actions with equal probability, independent of the action-value estimates.

> incremental update rule

NewEstimate <- OldEstimate + StepSize[Target - OldEstimate]

> 



## References:

[1] Sutton, Richard S., and Andrew G. Barto. Reinforcement learning: An introduction. MIT press, 2018.
