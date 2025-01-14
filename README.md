# CNN_Pruning_Experiment
An examination into using neural network pruning techniques on a simple CNN based on Li et Al 2017 (https://arxiv.org/abs/1608.08710)

The work here pruned a CNN with more than enough layers to complete a simple MNIST classification test. It examines the quantitative and qualitative impact of dropping filters with weights posting the lowest aggregate F1 scores. Qualitative impacts are reflected by visualizing the effects of fine tuning pruned networks. This simple experiment for a class serves as a first step to researching filtering techniques for more advanced applications.

Example of qualitative effects of pruning:

![image](https://github.com/user-attachments/assets/dd8b3fba-ebfd-46b3-b68e-0b62f69c7158)
