# Machine Learning For Strong Gravity

Short course for the Group meeting: "State of the art techniques in Strong gravity"

Sāo Pedro do Sul (Portugal), 26-28 April 2023

Meeting website: http://gravitation.web.ua.pt/index.php/node/4326

## Lectures:

### 1. Physics-informed neural networks (PINNs)
<a href="https://colab.research.google.com/github/raimonluna/MachineLearningForStrongGravity/blob/main/Lecture1_Physics_Informed_Neural_Networks.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

1. How to use PINNs to solve differential equations, including ODEs, PDEs and eigenvalue problems.<br>Original paper:<br>

 - Maziar Raissi, Paris Perdikaris, George Em Karniadakis, <i>Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations</i>, Journal of Computational Physics, 378, 686-707, 2019. https://arxiv.org/abs/1711.10561
 
2. How these can be used, for instance, for the computation of QNMs.<br>Original paper:<br>

 - Raimon Luna, Juan Calderón Bustillo, Juan José Seoane Martínez, Alejandro Torres-Forné, José A. Font, <i>Solving the Teukolsky equation with physics-informed neural networks
</i>, Phys.Rev.D 107 (2023) 6, 064025, 2023. https://arxiv.org/abs/2212.06103

### 2. Autoencoders and Generative Adversarial Networks (GANs)
<a href="https://colab.research.google.com/github/raimonluna/MachineLearningForStrongGravity/blob/main/Lecture2_Autoencoders_and_Generative_Adversarial_Networks.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

1. How to reduce the dimensionality of data by finding an appropriate basis of vectors.
2. How autoencoders "compress" the data by automatically identifying the governing parameters.
3. How we can use GANs to generate samples from the same distribution as the training data.<br>Original paper:<br>

 - Felipe F. Freitas, Carlos A. R. Herdeiro, António P. Morais, António Onofre, Roman Pasechnik, Eugen Radu, Nicolas Sanchis-Gual, Rui Santos, <i>Generating gravitational waveform libraries of exotic compact binaries with deep learning</i>, 2022. https://arxiv.org/abs/2203.01267

### 3. Learning Orbital Dynamics from Gravitational Waveforms
<a href="https://colab.research.google.com/github/raimonluna/MachineLearningForStrongGravity/blob/main/Lecture3_Learning_Orbital_Dynamics_and_Fourier_Neural_Operators.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

1. How we can learn the corrections to the Newtonian equations of motion by analyzing gravitational waves.<br>
  Original paper:<br>
  
 - Brendan Keith, Akshay Khadse, and Scott E. Field, <i>Learning orbital dynamics of binary black hole systems from gravitational wave measurements</i>, Phys. Rev. Research 3, 043101, 2021. https://arxiv.org/abs/2102.12695
 
 
2. How we can use Fourier Neural Operators to learn the solution of a differential equation from examples.<br>
  Original papers:<br>
  
 - Li, Z., Kovachki, N., Azizzadenesheli, K., Liu, B., Bhattacharya, K., Stuart, A., and Anandkumar A. , “Fourier Neural Operator for Parametric Partial Differential Equations”, ICLR, 2021. https://arxiv.org/abs/2010.08895
  
 - Kovachki, N., Li, Z., Liu, B., Azizzadenesheli, K., Bhattacharya, K., Stuart, A., and Anandkumar A. , “Neural Operator: Learning Maps Between Function Spaces”, , JMLR, 2021. https://arxiv.org/abs/2108.08481.

