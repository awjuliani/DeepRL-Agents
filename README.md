# Deep Reinforcement Learning Agents

This repository contains a collection of reinforcement learning algorithms written in Tensorflow. The ipython notebook here were written to go
along with a still-underway tutorial series I have been publishing on [Medium](https://medium.com/@awjuliani/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0#.4gyadb8a4).
If you are new to reinforcement learning, I recommend reading the accompanying post for each algorithm.

The repository currently contains the following algorithms:
* **Q-Table** - An implementation of Q-learning using tables to solve a stochastic environment problem.
* **Q-Network** - A neural network implementation of Q-Learning to solve the same environment as in Q-Table.
* **Simple-Policy** - An implementation of policy gradient method for stateless environments such as n-armed bandit problems.
* **Contextual-Policy** - An implementation of policy gradient method for stateful environments such as contextual bandit problems.
* **Policy-Network** - An implementation of a neural network policy-gradient agent that solves full RL problems with states and delayed rewards, and two opposite actions (ie. CartPole or Pong).
* **Vanilla-Policy** - An implementation of a neural network vanilla-policy-gradient agent that solves full RL problems with states, delayed rewards, and an arbitrary number of actions.
* **Model-Network** - An addition to the Policy-Network algorithm which includes a separate network which models the environment dynamics.
* **Double-Dueling-DQN** - An implementation of a Deep-Q Network with the Double DQN and Dueling DQN additions to improve stability and performance.
* **Deep-Recurrent-Q-Network** - An implementation of a Deep Recurrent Q-Network which can solve reinforcement learning problems involving partial observability.
* **Q-Exploration** - An implementation of DQN containing multiple action-selection strategies for exploration. Strategies include: greedy, random, e-greedy, Boltzmann, and Bayesian Dropout.
* **A3C-Doom** - An implementation of Asynchronous Advantage Actor-Critic (A3C) algorithm. It utilizes multiple agents to collectively improve a policy. This implementation can solve RL problems in 3D environments such as VizDoom challenges.
