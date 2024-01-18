# Block Breaker: Using Reinforcement Learning

This repository contains the code for the project report on using reinforcement learning to play the game "Tetris"

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)

## Introduction
In this project, we explore the application of reinforcement learning techniques to train an agent to play the game Block Breaker. The goal is to develop an AI agent that can learn to play the game effectively through trial and error. Various method of reinforcment learning explored. Code can be found in directories
1. Q-learning (Failed)
2. DQN (Without Hueristics) (Failed)
3. DQN (With Hueristics) 

Credits for the environment to setup the environment
1. Q-learning & DQN (Without Heuristics) : GYM Tetris https://gymnasium.farama.org/environments/atari/tetris/
2. DQN (With Heuristics): https://github.com/uvipen/Tetris-deep-Q-learning-pytorch

## Installation
To run the code in this repository, you need to have the following dependencies installed:
- Python 3.x 
- CV2
- Pytorch
- numpy
- gymnasium[accept-rom-license, atari]  *(pip install "gymnasium[accept-rom-license, atari]")*
- matplotlib

## Usage

Clone the repo, in the directory of DQN(With Heuristics) run the train.py to train the model. It should take around 5 mins. A model will be saved in root directory. Run the saved model using test.py and visualize.

## Demo

DQN Heuristic 
![](demo.gif)



