# NLA project

In this notebook we will implement recommendation system based on Slope-One and SVD algorithms

The original paper of [Slope-one](https://arxiv.org/abs/cs/0702144) algorithm

We will explore [Movielens 100k dataset](https://grouplens.org/datasets/movielens/100k/) and compare the accuracy rate of the recommendation system built with 2 techiques:
1. The only Slop-One
2. SVD (low rank approximation) + Slope-One on the reduced matrix (The idea is taken from [this](https://www.atlantis-press.com/proceedings/mcei-15/25840929) paper)

