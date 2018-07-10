# Deep Q-network
Keras implementation of DQN (DQN.ipynb) for MsPacman-v0 from OpenAI Gym.

Implements Deep Q-network (DQN) in Keras following the architecture proposed in the 2013 paper by V. Mnih et al., "Playing Atari with Deep Reinforcement Learning": arXiv:1312.5602. See: http://www.davidqiu.com:8888/research/nature14236.pdf

The agent learns to play the MsPacman-v0 Gym environment.

![Alt text](mspacman.jpg?raw=true "Title")

I modified the example found from https://keon.io/deep-q-learning/ by implementing the CNN model, target model logic, and frame averaging (among other things).

Hyperparameters were chosen according to the original paper as well as from https://github.com/ageron/tiny-dqn which also provided the image preprocessing method.  One key trick I found lead to better policies was introducing a fixed penalty of -1 at each action which did not naturally have a reward.

---
# Double Deep Q-network
Double Deep Q-network (DDQN.ipynb) is implemented.  See: https://arxiv.org/pdf/1509.06461.pdf

---
# Future Work
* Try different Atari environments
* Experiment with hyperparameters
* Classical algorithm problems (learn functions)
