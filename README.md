# Function Approximation using general neural network

function approximation program for 5 kinds of function – linear, quadratic, cubic, polynomial (x4) and trigonometric (Sinusoidal and Cosine)

## Dataset division

*Training set (60%)
Cross-Validation set (20%)
Test set (20%)*

## NN-architecture
|Polynomial Function| Trigonometric Function  |
|--|--|
| ![NN architecture for Polynomial Function](https://github.com/nhjoy/ANN-Function-Approx/blob/main/img/poly_nn.png) | ![NN architecture for Trigonometric Function](https://github.com/nhjoy/ANN-Function-Approx/blob/main/img/tri_nn.png) |
|Input = 8; Hidden = 16; Output = 1|Input = 16; Hidden = 16; Output = 1|


Where **rectifier or ReLU (Rectified Linear Unit) activation function** used.

## Training Model Details

 - Optimization algorithm = **Adam Optimizer**
 - Loss function = **Mean squared error (MSE)**

## How to use

the code is written in Interective Jupyter Notebook. The whole code segmented into sections. To run any part click the run or execute button. It is suggested to run the code on Google colab. It has all the necessary python environment preinstalled which saves one from tedious installation process.

## Process to run the codes using google colab

1. Go to https://colab.research.google.com/ and sign in with you gmail account.
2. Create a new Notebook.
3. write and execute the following line to import all the code from this repository 
```

```
5. 
