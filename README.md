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
