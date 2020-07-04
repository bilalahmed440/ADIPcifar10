% Image Denoising Using a U-net

This implementation is in Jupyter Notebook using the PyTorch framework. To download Jupyter Notebook, follow
Instructions from https://jupyter.org/install
Pre-req: Python, pytorch package 

This implementation uses Python3. It can be downloaded from https://www.python.org/downloads

PyTorch can be installed from https://pytorch.org/get-started/locally/

To run Jupyter notebook, type 'jupyter notebook' from the terminal and the notebook
should open

The following packages are needed: numpy, matplotlib, torch

pytorch_prototyping.py is directly downloaded from the following GitHub repo https://github.com/vsitzmann/pytorch_prototyping

The dataset used is CIFAR-10 which contains 60,000 images of 32*32 resolution and is 
widely used in ML and CV applications: https://www.cs.toronto.edu/~kriz/cifar.html

To get a better understanding of PyTorch and how CIFAR-10 is read in, follow the tutorial
given here: https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html

Open cifar10_denoising.ipynb in jupyter and run the code block 

% To choose optimizer in Jupiter notebook while running, the optimizer options are commented out. Comment out the optimizers you don't want to run. If the code is run
without any changes, the Adam optimizer will be implemented by default with learning rate 0.001

% the default noise is set to Gaussian noise with sigma=0.05. That can be changed according to user preference. 2 other implementations with Gaussian noise and Poisson noise are also implemented but commented out. Comment out the noise you don't want to use and run the code block accordingly.

% The default epoch is set to 1 but can be increased


