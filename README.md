# Using Multi-Agent Reinforcement Learning to learn Tic-Tac-toe

A normal Reinforcement Learning problem deals with Markov Decision Processes ([MDP](https://towardsdatascience.com/introduction-to-reinforcement-learning-markov-decision-process-44c533ebf8da)), but when one chooses to use Multi-Agent RL, the agent not only learns from the environment but also takes into account the actions of other agent present in the environment.

In this model there are two main tasks:
* Create 2 instances of a single Agent and let it play against each other (Train)
* Test it against a Human Player to check it's efficiency

<!-- ### Train -->


## Dependencies

NumPy, Matlplotlib & Pickle (Comes pre-installed with standard Python3)

To install Numpy & Matplotlib using [pip](https://pip.pypa.io/en/stable/) 

```bash
pip install numpy
pip install matplotlib
```