# Reinforcement-Learning

Course Objectives

This course aims at developing an understanding about the fundamental concepts in defining
and simulating reinforcement learning, identifying, understanding and implementing various
reinforcement learning algorithms.


Course Outcomes 

CO1: Basic and deep understanding on reinforcement learning
CO2: Illustrate Markov Decision related algorithms.
CO3: Implement Monte Carlo methods for prediction 
CO4: Analyze temporal-difference learning and eligibility traces.


Unit-1 : Reinforcement Learning Problem and Multi-arm Bandits   

Definition of a stochastic multi-armed bandit, A k-armed Bandit Problem, Definition of
regret, Tracking a Nonstationary Problem, Upper-Confidence-Bound Action Selection, KL-
UCB, Gradient Bandits. 

Lab:
1. Implement Multi-Armed Bandit Problem from Scratch in Python
2. Implement Tracking Nonstationary Bandit Problem
Self-study topics: Basics of probability and linear algebra.


Unit-2 : Finite Markov Decision Processes

Markov Decision Problem, policy, and value function, Reward models (infinite discounted,
total, finite horizon, and average), Episodic & continuing tasks, Bellmans optimality
operator, and Value iteration & policy iteration
Lab: Implement Markov Decision Process (MDP) Simulation and Value Iteration
          Develop a program to perform policy evaluation and improvement for a given MDP

          
Unit-3 : Monte Carlo Methods        

The Reinforcement Learning problem, prediction and control problems, Model-based
algorithm, Monte Carlo methods for prediction, and Online implementation of Monte Carlo
policy evaluation 

  Lab:
Implement Model-Free Prediction & Control With Monte Carlo (MC).
Extend the reinforcement learning environment to support model-based algorithms for
decision-making.


Unit-4 : Temporal-Difference Learning 

Bootstrapping; TD(0) algorithm; Convergence of Monte Carlo and batch TD(0) algorithms;
Model-free  control: Q-learning, Sarsa, Expected Sarsa

Lab: Implement the TD(0) algorithm for temporal-difference learning in a simulated
environment, where an agent interacts with states and receives rewards.
Implement Q-learning and SARSA algorithms for action-value estimation and policy
improvement.


Unit-5 : Eligibility Traces      

n-step returns; TD(λ) algorithm; Need for generalization in practice; Linear function
approximation and  geometric view; Linear TD(λ). Tile coding; Control with function
approximation; Policy search; Policy  gradient methods; Experience replay; Fitted Q
Iteration; Case studies.

Lab: Implement the TD(λ) algorithm with eligibility traces for temporal-difference learning
in a simulated environment.
Implement policy gradient methods for policy search, such as REINFORCE or actor-critic
algorithms.


Text Books and Reference Books
[1] Sutton, Richard S., and Andrew G., Barto, “Reinforcement learning: An
introduction,” First Edition, MIT press 2020
[2] Sugiyama, Masashi.“Statistical reinforcement learning: modern machine learning
approaches,” First Edition, CRC Press,2015 
Essential Reading / Recommended Reading
[1] Lattimore, T. and C. Szepesvári. “Bandit algorithms,” First Edition, Cambridge
University
[2] Press. 2020
[3] Boris Belousov, Hany Abdulsamad, Pascal Klink, Simone Parisi, and Jan Peters
“Reinforcement Learning Algorithms: Analysis and Applications,” 
[4] First Edition, Springer 2021
[5] Alexander Zai and Brandon Brown “Deep Reinforcement Learning in Action,” First
Edition,Manning Publications 2020
