# Model and Policy Networks

Overview
=========
Generally, the policies in a reinforcement learning problem are learnt by interacting with the simulated(game) environment. But when posed with the real environments, we may exhaust time and energy and may not be practical in the initial phase of learning because physical environments take time to navigate, and the physical rules of the world prevent things like easy environment resets from being feasible.

This problem can be partially solved by learning the dynamics of the real environment with the help of a neural network called Model neural network and simultaneously learn the best possible policies to maximize rewards using Model environment. On reaching a threshold, we can start executing our policies on the real environment.

Dependencies 
============
* Jupyter Notebook
* Numpy
* OpenAI Gym (https://gym.openai.com/docs/)
* Tensorflow (https://www.tensorflow.org/install/)

Credits
============
Most of the conceptual and programmatic understanding is borrowed from the Reinforcement Learning Series by Arthur Juliani [here](https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0).
