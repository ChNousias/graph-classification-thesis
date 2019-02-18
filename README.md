Graph Classification using Neural Networks
=================
This repository is part of the thesis project **"Graph Classification using Neural Networks"** carried by me (Nousias Ch.) in the Aristotle University of Thessaloniki (A.U.Th.) in the interdepartmental postgraduate programme of studies "Advanced Computer and Communication Systems" under the supervision of Emeritus Proffesor Vasileios Petridhs. The thesis project is to be presented in February 2019.

The repository includes implementations for carrying Graph Classification on benchmark datasets from the field of bioinformatics with:
- **Graph Kernels**
- **Neural Networks on Graphs**

### Graph Kernel Libraries
Basic tool for the graph kernel implementations was the [GraKeL](https://github.com/ysig/GraKeL/) library by [Siglidis et al. (2018)](https://arxiv.org/abs/1806.02193), and [Scikit Learn](https://github.com/ysig/GraKeL/) 

### Graph Neural Networks
As basic framework for carrying graph classification with Neural Networks was the [graph_nets](https://github.com/deepmind/graph_nets) library developed by DeepMind as described in the corresponding paper [Relational inductive biases, deep learning, and graph networks](https://arxiv.org/abs/1806.01261).

Datasets were cloned by the Pytorch implementation of the **"Deep Graph Convolutional Neural Network (DGCNN)"**, work of [Zhang et al. (2018)]("https://github.com/muhanzhang/dgcnn"). These versions were preferred over those included in the [TU Dortmund repository](https://ls11-www.cs.tu-dortmund.de/staff/morris/graphkerneldatasets) for graph datasets as were deemed mmore consistent to each other without the need for repeating basic steps of preprocessing for each different dataset.


Setting Up
=================

### Conda Environments
Each implementation was done within its own conda environment which can be deployed by the accompanying environment yaml file:
- Graph kernel environment
- Graph Networks env

The environments can be deployed by using some basic [conda functionality](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file).

Deploying
=================
Both implementations were deployed and run in **Ubuntu OS 18.04** as the [Sonnet](https://github.com/deepmind/sonnet) library which is thoroughly used by the **graph_nets** library which is compatible only with Linux/Mac OS X, using Jupyter Notebooks. Training was carried on multiple CPU cores, locally as well as on VM instances on Azure Cloud. 


Version History
=================
#### 1.0
- This is a concluded repository accompanying a commited thesis project. Therefore, no further changes will be carried instead of possible minor fixes.
