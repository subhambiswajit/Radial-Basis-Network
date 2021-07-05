# Radial-Basis-Network
This repository explains the mechanism of Radial Basis Neural Network using a Gaussian kernel for non-linear transformation of samples

#### a radial basis function network is an artificial neural network that uses radial basis functions as activation functions. The output of the network is a linear combination of radial basis functions of the inputs and neuron parameters. Radial basis function networks have many uses, including function approximation, time series prediction, classification, and system control. They were first formulated in a 1988 paper by Broomhead and Lowe, both researchers at the Royal Signals and Radar Establishment. 

Courtesy: [Radial Basis Neural Network](https://en.wikipedia.org/wiki/Radial_basis_function_network)

### Implementation:

#### Data generation policy: The samples are generated using random seeding of system time using the following formula. <br> 
![data generation policy](img/q3_1.PNG)

### Kernel used for non linear transformation: Gaussian Kernel.
<br>

### Initial weights between hidden layer and output layer are randomized.
<br>

### Final weights are calculated using Matrix Inversion, after we decide on the mean and sigma (distance) parameters of K datapoints in the hidden layer.
<br>

### Case Studies
#### Case study: is made on selection process of K datapoints. 
#### Case Study: is made on varying the value of sigma (distance) parameter of Gaussian Kernels. 
### 

### Assumptions
#### It is assumed that sigma (distance) parameter is same for K nodes in the hidden layer, for any Case study
<br>

![0](RadialBNN/0001.jpg)
![1](RadialBNN/0002.jpg)
![2](RadialBNN/0003.jpg)
![3](RadialBNN/0004.jpg)
![4](RadialBNN/0005.jpg)
![5](RadialBNN/0006.jpg)
![6](RadialBNN/0007.jpg)
![7](RadialBNN/0008.jpg)
![8](RadialBNN/0009.jpg)
![9](RadialBNN/0010.jpg)
![10](RadialBNN/0011.jpg)
![11](RadialBNN/0012.jpg)
![12](RadialBNN/0013.jpg)
![13](RadialBNN/0014.jpg)
![14](RadialBNN/0015.jpg)
![15](RadialBNN/0016.jpg)
