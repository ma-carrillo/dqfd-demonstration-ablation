# dqfd-demonstration-ablation

Ablation study of the impact of demonstration dataset size in Deep Q-learning from Demonstrations (DQfD), using Snake and Flappy Bird environments.

## Repository Structure

* **DQFD_FlappyBird.ipynb**
  Contains the training script for Flappy Bird, as well as the results analysis for this environment.

* **DQFD_Snake.ipynb**
  Contains the training script for Snake and the corresponding analysis of the experimental results.

* **getHumanExp.ipynb**
  Contains the scripts used to collect and store human demonstration data.
  The recorded experiences are saved as `.pkl` files and are used for DQfD pretraining.

