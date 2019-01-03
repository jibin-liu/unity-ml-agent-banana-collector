# Banana Collector

<img src="img/trained-agent.gif" width="500">

This project shows the work of training a reinforcement learning agent to navigate and collect bananas in Unity ML-agent environment.

### Introduction
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of our agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.
1 - move backward.
2 - turn left.
3 - turn right.

The task is episodic, and in order to solve the environment, our agent must get an average score of +13 over 100 consecutive episodes.

### Python environment
Python 3.6 is used to conduct the work. However, Python 3.5 should also work.

To prepare the Python environment, first create a virtual environment using your favoured package mangement tool, then `cd` to the repo's root directory and run the following command:

```
pip -q install ./python
```

### Unity environment
