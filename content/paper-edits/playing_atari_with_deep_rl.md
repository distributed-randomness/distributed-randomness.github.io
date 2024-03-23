+++
title = "Playing Atari with Deep Reinforcement Learning"
date = 2023-04-27
updated = 2023-04-27
draft = false
in_search_index = true
template = "page.html"

[taxonomies]
  # tags = ["shards", "plb"]
  categories = ["rl"]

[extra]
math = true
+++


[Paper](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)


However reinforcement learning presents several challenges from a deep learning perspective. Firstly, most successful deep learning applications to date have required large amounts of hand- labelled training data. RL algorithms, on the other hand, must be able to learn from a scalar reward signal that is frequently sparse, noisy and delayed. The delay between actions and resulting rewards, which can be thousands of timesteps long, seems particularly daunting when compared to the direct association between inputs and targets found in supervised learning. Another issue is that most deep learning algorithms assume the data samples to be independent, while in reinforcement learning one typically encounters sequences of highly correlated states. Furthermore, in RL the data distribu- tion changes as the algorithm learns new behaviours, which can be problematic for deep learning methods that assume a fixed underlying distribution.

__Edited__


