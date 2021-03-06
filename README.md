# Deep-Neural-Networks-with-Multi-Branch-Architectures-Are-Less-Non-Convex

This is the code for the paper [Deep Neural Networks with Multi-Branch Architectures Are Less Non-Convex](https://arxiv.org/pdf/1806.01845.pdf) in AISTATS 2019 by Hongyang Zhang, Junru Shao, and Ruslan Salakhutdinov.

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
To get started, cd into the directory. Then run the scripts: 
* fully_connected.py is a demo on plotting the landscape of multi-branch neural network where each sub-network is a full-connected network with ReLU activation functions and the dataset is synthetic.
* VGG.py is for running the multi-branch neural network based on VGG-9 on CIFAR-10 dataset.

## Using the code
The command `python fully_connected.py --help` gives the help information about how to run the code that produces landscape, and `python VGG.py --help` explains how to run the multi-branch neural network based on VGG-9.

## Running Example
<p align="center">
    <img src="example.png" width="800"\>
</p>

## Reference
For technical details and full experimental results, see [the paper](https://arxiv.org/abs/1806.01845).
```
@inproceedings{Zhang2019deep, 
	author = {Hongyang Zhang and Junru Shao and Ruslan Salakhutdinov}, 
	title = {Deep Neural Networks with Multi-Branch Architectures Are Less Non-Convex}, 
	booktitle = {International Conference on Artificial Intelligence and Statistics},
	year = {2019}
}
```

## Contact
Please contact hongyanz@cs.cmu.edu if you have any question on the codes.
