# Federated Learning for Image Classification


## FedAvg, FedProx, and ADMM-Based Algorithms with IID and Non-IID Data Distributions


In this project, we will consider the problem of federated learning (FL) for image classification. The federated variant we consider is horizontal (sample-based), i.e., the feature space is shared among agents, while their samples are different. Each agent trains its own local model, and sends its local weights to the coordinator who builds the global and aggregated model. We implement three different federated algorithms; federated averaging (FedAvg), FedProx, and Linearized inexact ADMM-based federated learning (LIADMM). We train these algorithms using both iid and non-iid distributions of distributed Fashion MNIST dataset, and compare their validation performance with the centralized training paradigm.
