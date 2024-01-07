# Reinforcement Learning

Reinforcement Learning is a type of Machine Learning technique that enables an agent to learn in an interactive environment by trial and error using feedback from its own actions and experiences.
einforcement learning uses rewards and punishments as signals for positive and negative behavior.

Some key terms that describe the basic elements are given below:

**Environment** — Physical world in which the agent operates
**State** — Current situation of the agent
Reward — Feedback from the environment
Policy — Method to map agent’s state to actions
Value — Future reward that an agent would receive by taking an action in a particular state

## Q Learning

Q Learning is a Reinforcement learning policy that will find the next best action, given a current state. It chooses this action at random and aims to maximize the reward.
To do this, it may come up with rules of its own or it may operate outside the policy given to it to follow. This means that there is no actual need for a policy, hence we call it off-policy model.
The Q-learning algorithm uses a Q-table of State-Action Values (also called Q-values). This Q-table has a row for each state and a column for each action.

In this Taxi Example, Q learning algorithm is used.

