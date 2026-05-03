# Elements of Machine Learning & Deep Learning

This repository contains a collection of hands-on Jupyter Notebooks developed for machine learning and deep learning. The projects range from foundational statistical modeling and optimization techniques to the core mechanics of deep neural networks and modern transformer architectures.

##  Repository Contents

### 1. Machine Learning Foundations
* **`Linear_Regression.ipynb`**
  A practical implementation of Linear Regression using the California Housing dataset. This notebook covers data loading, feature exploration using `pandas`, and model fitting/evaluation using `scikit-learn`.
* **`Generalization_Model_Selection_and_Beyond_Linearity.ipynb`** 
  Focuses on preventing overfitting and selecting the best model. It implements custom K-fold cross-validation, evaluates Ridge vs. Lasso regression using optimal lambda values, and explores non-linear modeling through Polynomial Regression and Splines.
* **`Line_Search_and_Gradient_Descent.ipynb`**
  Visualizes 1D loss functions and demonstrates how optimization algorithms like Line Search and Gradient Descent iteratively update parameters to find global/local minima.

### 2. Deep Learning Core Mechanics
* **`Backpropagation_in_Toy_Model.ipynb`**
  A conceptual breakdown of the chain rule. Instead of a full neural network, this notebook performs backpropagation on a complex mathematical function (chaining sine, cosine, and exponential operations) to build an intuitive understanding of gradients.
* **`Backpropagation.ipynb`**
  A complete implementation of the forward and backward passes for a Deep Neural Network from scratch. It mathematically verifies the calculated gradients against finite differences to ensure accuracy.
* **`Neural_Netowork_Initialization.ipynb`**
  An interactive demonstration of why weight initialization is critical. By passing data through a 50-layer network, it visualizes the *vanishing gradient* (low variance uniform), *exploding gradient* (high variance uniform), and *stable gradient* (He Initialization) problems.

### 3. Advanced Architectures (Transformers)
* **`Tokenization.ipynb`**
  An introduction to how Large Language Models process text. It demonstrates vocabulary initialization and iterative token merging (similar to Byte-Pair Encoding) to efficiently compress character sequences into tokens.
* **`Multihead_Self-Attention.ipynb`**
  A from-scratch implementation of the core mechanism behind Transformers. It shows how queries, keys, and values are computed, scaled, and combined using softmax weights to capture contextual relationships across sequences.
