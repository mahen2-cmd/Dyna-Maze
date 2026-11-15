# Dyna-Q and Dyna-Q+ in changing mazes

Model-based reinforcement learning from scratch: a maze environment, **Dyna-Q** (Q-learning plus planning updates from a learned model), and **Dyna-Q+** (an exploration bonus for state-action pairs not tried in a while), tested on a maze whose layout **changes mid-training**.

The notebook includes my notes on where Dyna-Q+ struggles in non-stationary environments, and an idea for a stochastic variant combining optimistic initialisation with the time-since-visit bonus.

Stack: Python, NumPy, Gymnasium, Matplotlib.
