# DOL-Project2
Executed GOSGD: A Distributed Deep Learning Algorithms for an Image Classification Task- Distributed Optimization and Learning(DOL) Course Project

## Overview


In this project, we implemented distributed deep learning algorithms as one case study of distributed optimization algorithms both for the data-parallel and data-distributed cases. 

We used the CIFAR10 dataset and a convolution neural network to accomplish this. Our first step in training the network was centralized, as is standard in deep learning. Then we implemented the GoSGD algorithm, one of the most famous algorithms in distributed deep learning. In the following, different weight matrices were tested. Then, we assumed that the communication between clients was noisy, and the result was compared with previous cases. Finally, we implemented another gossip-based distributed optimization algorithm, SGP, and compared the result with GoSGD.  

In the second part, we consider the case in which the data is distributed between clients, but despite the federated learning, there is no coordinator. For this part, we used a modified version of the GoSGD Algorithm and distributed the data in an iid and uniform manner between clients. Finally, the results are compared with the first project. 
