# Deep Q-network
Keras implementation of DQN for MsPacman-v0 from OpenAI Gym.

Implements Deep Q-network (DQN) in Keras following the architecture proposed in the 2013 paper by V. Mnih et al., "Playing Atari with Deep Reinforcement Learning": arXiv:1312.5602.

The agent learns to play the MsPacman-v0 Gym environment.

![Alt text](mspacman.jpg?raw=true "Title")

I modified the example found from https://keon.io/deep-q-learning/ by implementing the CNN model and target model logic (among other things).

Hyperparameters were chosen according to the original paper as well as from https://github.com/ageron/tiny-dqn which also provided the image preprocessing method.
