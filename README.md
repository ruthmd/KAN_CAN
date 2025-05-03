# Kolmogorov-Arnold Networks

[Kolmogorov-Arnold Networks (KANs)](https://arxiv.org/abs/2404.19756) are a novel neural network architecture inspired by the Kolmogorov-Arnold representation theorem from the 1950s. Unlike traditional Multi-Layer Perceptrons (MLPs) that use fixed activation functions on nodes ("neurons"), KANs have learnable activation functions on edges ("weights"). KANs replace every weight parameter with a univariate function parametrized as a spline. This seemingly simple change makes KANs particularly powerful for function approximation and modeling complex relationships.


### This repo consits of implemntations of applying Kolmogorov-Arnold Networks for finance applications 
- Option pricing and Greeks calculation
- Yield curve modeling
- Risk factor decomposition
- Time series forecasting
- Portfolio optimization
- Market regime detection



Refrences - 
 - [pykan](https://github.com/KindXiaoming/pykan)