*Thank you for Curt Park's open source, which has been adapted from open source code*
# Rainbow-MindSpore!

This is a step-by-step tutorial from DQN to Rainbow.
Every chapter contains both of theoretical backgrounds and object-oriented implementation. Just pick any topic in which you are interested, and learn! You can execute them right away with Colab even on your smartphone.

Please feel free to open an issue or a pull-request if you have any idea to make it better. :)

>If you want a tutorial for policy gradient methods, please see [PG is All You Need](https://github.com/MrSyee/pg-is-all-you-need).

## Contents
01. DQN [[NBViewer](https://github.com/mindspore-courses/Rainbow-MindSpore/blob/main/01.dqn.ipynb)]
02. DoubleDQN [[NBViewer](https://github.com/mindspore-courses/Rainbow-MindSpore/blob/main/02.double_q.ipynb)]
03. PrioritizedExperienceReplay [[NBViewer](https://github.com/mindspore-courses/Rainbow-MindSpore/blob/main/03.per.ipynb)]
04. DuelingNet [[NBViewer](https://github.com/mindspore-courses/Rainbow-MindSpore/blob/main/04.dueling.ipynb)]
05. NoisyNet [[NBViewer](https://github.com/mindspore-courses/Rainbow-MindSpore/blob/main/05.noisy_net.ipynb)]
06. CategoricalDQN [[NBViewer](https://github.com/mindspore-courses/Rainbow-MindSpore/blob/main/06.categorical_dqn.ipynb)]
07. N-stepLearning [[NBViewer](https://github.com/mindspore-courses/Rainbow-MindSpore/blob/main/07.n_step_learning.ipynb)]
08. Rainbow [[NBViewer](https://github.com/mindspore-courses/Rainbow-MindSpore/blob/main/08.rainbow.ipynb)]

## Prerequisites
This repository is tested with python 3.7+
MindSpore 2.1
```
git clone https://github.com/Curt-Park/rainbow-is-all-you-need.git
cd rainbow-is-all-you-need
make setup
```

## How to Run
```
jupyter lab
```

## Related Papers

01. [V. Mnih et al., "Human-level control through deep reinforcement learning." Nature, 518
(7540):529–533, 2015.](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf)
02. [van Hasselt et al., "Deep Reinforcement Learning with Double Q-learning." arXiv preprint arXiv:1509.06461, 2015.](https://arxiv.org/pdf/1509.06461.pdf)
03. [T. Schaul et al., "Prioritized Experience Replay." arXiv preprint arXiv:1511.05952, 2015.](https://arxiv.org/pdf/1511.05952.pdf)
04. [Z. Wang et al., "Dueling Network Architectures for Deep Reinforcement Learning." arXiv preprint arXiv:1511.06581, 2015.](https://arxiv.org/pdf/1511.06581.pdf)
05. [M. Fortunato et al., "Noisy Networks for Exploration." arXiv preprint arXiv:1706.10295, 2017.](https://arxiv.org/pdf/1706.10295.pdf)
06. [M. G. Bellemare et al., "A Distributional Perspective on Reinforcement Learning." arXiv preprint arXiv:1707.06887, 2017.](https://arxiv.org/pdf/1707.06887.pdf)
07. [R. S. Sutton, "Learning to predict by the methods of temporal differences." Machine learning, 3(1):9–44, 1988.](http://incompleteideas.net/papers/sutton-88-with-erratum.pdf)
08. [M. Hessel et al., "Rainbow: Combining Improvements in Deep Reinforcement Learning." arXiv preprint arXiv:1710.02298, 2017.](https://arxiv.org/pdf/1710.02298.pdf)
