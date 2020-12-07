# dpprl

A DPP implementation on Deep Reinforcement Learning for Movies Recommendation System from the paper:

Zhao, X., Zhang, L., Xia, L., Ding, Z., Yin, D., & Tang, J. (2019). Deep reinforcement learning for list-wise recommendations.

The implementation is heavily built on the following code repo: 

egipcy. (2020). List-wise recommendation framework based on deep reinforcement learning. https://github.com/egipcy/LIRD. GitHub.

This decision was made to run the experiment in the available time, and to built on top of giants to maximize scientific contribution.

# Requirements

* Python 3
* Tensorflow 1.15
* Numpy
* Scipy
* Dppy

# Usage

Install required packages<br>
run python deep-dpprl-dpp.py

# Configurations

The dataset is split into train, validation, and test sets to make the experiment as valid as possible.<br>
By tuning the nb_episodes parameter the model is tested on diversify performance through the episodes.

# Acknowledgments

This project is heavily built on the LIRD model, and by using the following papers:

* egipcy. (2020). List-wise recommendation framework based on deep reinforcement learning. https://github.com/egipcy/LIRD. GitHub.
* Zhao, X., Zhang, L., Xia, L., Ding, Z., Yin, D., & Tang, J. (2019). Deep reinforcement learning for list-wise recommendations.
* Gautier, G., Polito, G., Bardenet, R., & Valko, M. (2019). Dppy: Dpp sampling with python. Journal of Machine Learning Research, 20(180), 1-7.
* Liu, Y., Zhang, Y., Wu, Q., Miao, C., Cui, L., Zhao, B., . . . Guan, L. (2019). Diversity-promoting deep reinforcement learning for interactive recommendation. ArXiv, abs/1903.07826 .
