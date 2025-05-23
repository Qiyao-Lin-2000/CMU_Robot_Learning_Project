# CMU_Robot_Learning_Project

In this project we reproduce the training of DiffTORI and try to improve it.
The code for DiffTORI comes from:

https://github.com/wkwan7/DiffTORI

I tried changing helper.py and tdmpc.py in mbrl/src/algorithm to make the change.
It includes a version with the suffix mlpResNet, which is an improvement that complicates the original MLP and increases the residual structure to enhance its ability to capture complex information.
KL adds variational latent-space regularization to try to make the reward smoother.
