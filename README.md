Sparse Gaussian Process Classification with Variational Inference

Investigating a sparse approach to Gaussian process classification with variational inference ([Hensman et al., 2015](https://arxiv.org/abs/1411.2005)).
We compare this approach with linear logistic regression as well as with Gaussian process classification (GPC) with variational inference only and with Laplace approximations.

We showcase the reduced computational complexity and competitive model performance of this approach through two simulated datasets and one real dataset consisting of handwritten digits from the U.S. Postal Service.

## Setting up environment with necessary packages

```
conda create --name GPC python=3.8
conda activate GPC

pip install GPy
pip install statsmodels
pip install sklearn
pip install jupyter
```
