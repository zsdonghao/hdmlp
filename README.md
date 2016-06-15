# hdMLP
## A Powerful Multi-Layer Perceptron 
This easy-to-use library includes all advanced training methods, with tensor format. Large amount of network can be achieved by using this library including Sparse Autoencoder, Denosing Autoencoder, Rectifier Pre-train and so on. However, you should contact author before using the code and idea of this library.

DropNeuron was first implemented by this library which is aimed to train a small model from a large random initialized model, rather than 
compress or reduce a large trained model.

For TensorFlow version, please go to [TensorLayer](https://github.com/zsdonghao/tensorlayer#Overview).

 
### Training Methods:
> 1. Greedy Layer-Wise Pre-train
> 2. Fine-Tune
> 3. Dropout
> 4. DropNeuron
> 5. Autoencoder (AE)
> 6. Regression & Classification
> 7. Apache Spark
> 8. GPU Acceleration

### Activation Functions:
> 1. Rectifier	(if pre-train: reconstruction layer will be softplus)
> 2. Sigmoid		(if pre-train: reconstruction layer will be sigmoid)
> 3. Ramp Sigmoid  (if pre-train: reconstruction layer will be sigmoid)
> 4. All Others
> 5. Max-out (to do)

## License
Copyright (C) 2016 Hao Dong <hao.dong11@imperial.ac.uk> 

The code is a part of HDL project

The code can not be copied, distributed, modified and/or used for research and/or any commercial use without the express permission of Hao Dong


## Author:
Hao Dong 

Department of Computing & Data Science Institute
 
Imperial College London

> Note that: Dropneuron was published by Hao Dong, this is the first code to implement Dropneuron. Dropneuron is under review of NIPS.