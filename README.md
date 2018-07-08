# Deep-Neural-Networks-with-Multi-Branch-Architectures-Are-Less-Non-Convex

This is the code for the paper "Deep Neural Networks with Multi-Branch Architectures Are Less Non-Convex".

The code is written in python and requires numpy, torch, torchvision and the tqdm library.

## Install
This code depends on python 3.6, pytorch 0.3.1 and numpy. We suggest to install the dependencies using Anaconda or Miniconda. Here is an exemplary command:
```
$ wget https://repo.anaconda.com/archive/Anaconda3-5.1.0-Linux-x86_64.sh
$ bash Anaconda3-5.1.0-Linux-x86_64.sh
$ source ~/.bashrc
$ conda install pytorch=0.3.1
```

## Get started
To get started, cd into the directory. Then runs the scripts: 
* fully_connected.py is a demo on plotting the landscape of multi-branch neural network where each sub-network is a full-connected network with ReLU activation functions and the dataset is synthetic,
* VGG.py is for running the multi-branch neural network based on VGG-9 on CIFAR-10 dataset.

## Using the code
The command `python fully_connected.py --help` gives the help information about how to run the code that produces landscape, and `python VGG.py --help` explains how to run the multi-branch neural network based on VGG-9.

## Reference
For technical details and full experimental results, see [the paper](https://arxiv.org/abs/1806.01845).
```
@article{Zhang2018deep, 
	author = {Hongyang Zhang and Junru Shao and Ruslan Salakhutdinov}, 
	title = {Deep Neural Networks with Multi-Branch Architectures Are Less Non-Convex}, 
	booktitle = {arXiv preprint arXiv:1806.01845},
	year = {2018}
}
```

## Contact
Please contact junrus@cs.cmu.edu and hongyanz@cs.cmu.edu if you have any question on the codes.
