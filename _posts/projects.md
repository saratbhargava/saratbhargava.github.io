---
layout: post
title: Projects
---

# Deep Learning based Action Recognition from EEG Data
Explored various CNN, RNN, Conv-Recurrent Net architectures in Keras. Implemented data prepossessing techniques like Windowed cropping, Sub-sampling to obtain the best performance of 67% with stacked GRU compared to a base line model of 46% with Shallow CNN.

# SpaceInvaders using Deep RL
Implemented Dueling, Double DQN to play Atari Space Invaders game in tensorflow.Dueling DQN learned better hiding strategy than Double DQN when trained for similar duration of time in both RAM and Pixel versions of the game. They achieved an average score of 351.1 and 291.1 respectively.

# Deep Reinforcement learning based Path Tracking
Designed Deep RL based controller for Unicycle vehicle model using the DDPG algorithm to achieve continuous control in PyTorch.DDPG is more robust to action space noise than baseline LTV-MPC algorithm.

# Movie Recommender system
Implemented user-based K-NN, Latent factor based models like NNMF, SVD to predict movie rating in Movielens dataset. SVD performed better performance in terms of AUC.

# Unsupervised Spoken Term Detection
Trained GMM and RBM on MediaEval 2012 STD data set. Latent variables inferred from GMM’s and RBM’s are used as feature vectors to locate the best match for the query in speech corpus. Average Term Weighted Value increased from baseline performance of 16 (MFCC’s) to 33.6 and 34.5 respectively.
