Graph Classification using Neural Networks
=================
This repository is part of the thesis project **"Graph Classification using Neural Networks"** carried by me (Nousias Ch.) in the Aristotle University of Thessaloniki (A.U.Th.) in the interdepartmental postgraduate programme of studies "Advanced Computer and Communication Systems" under the supervision of Emeritus Professor Vasileios Petridhs. The thesis project is to be presented in February 2019.

The repository includes implementations for carrying Graph Classification on benchmark datasets from the field of bioinformatics with:

- **Neural Networks on Graphs**
- **Graph Kernels**

### Graph Neural Networks
Basic framework for carrying graph classification with Neural Networks was the [Graph Nets](https://github.com/deepmind/graph_nets) library developed by DeepMind as described in the corresponding paper **"Relational inductive biases, deep learning, and graph networks"**by [Battaglia et al.(2018)](https://arxiv.org/abs/1806.01261).

### Graph Kernel Libraries
Basic tool for the graph kernel implementations was the [GraKeL](https://github.com/ysig/GraKeL/) library by [Siglidis et al. (2018)](https://arxiv.org/abs/1806.02193) and [Scikit Learn](https://scikit-learn.org/stable/). 

Datasets were cloned by the Pytorch implementation of the **"Deep Graph Convolutional Neural Network (DGCNN)"**, work of [Zhang et al. (2018)](https://github.com/muhanzhang/dgcnn). These versions of graph datasets were preferred over those included in the [TU Dortmund repository](https://ls11-www.cs.tu-dortmund.de/staff/morris/graphkerneldatasets) as were deemed more consistent to each other without the need for repeating basic steps of importing and preprocessing for every dataset.


Setting Up
=================

### Conda Environments
Each implementation was done within its own conda environment specified by the accompanying environment yaml file:
- Graph kernels: graph_kernels.yml
- Graph Neural Networks: graph_networks_env.yml

The environments can be deployed by using some basic [conda functionality](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file).

Deploying
=================
Both implementations were deployed and run in **Ubuntu OS 18.04** as the [Sonnet](https://github.com/deepmind/sonnet) library which is used by the **graph_nets** library is compatible only with Linux/Mac OS X. Both implementations are on Jupyter Notebooks. Training was carried on multiple CPU cores, locally as well as on VM instances on Azure Cloud. 


Version History
=================
#### 1.0.0
- This is a concluded repository accompanying a commited thesis project. Therefore, no further changes will be carried instead of possible minor fixes.
