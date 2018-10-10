# Bayesian Learning

## Setup

* Install [Julia Language](https://julialang.org/) and Jupyter Notebook ([Anaconda3](https://www.anaconda.com/download/#macos))
* Install related packages in Julia REPL

    ```julia
    using Pkg

    Pkg.add("IJulia")
    Pkg.add("Distributions")
    Pkg.add("Optim")
    Pkg.add("PyCall")
    Pkg.add("PyPlot")
    ```

* Run Jupyter notebook

    ```shell
    $ jupyter notebook
    ```

## Variational Inference

1. [KL Divergence](http://nbviewer.jupyter.org/github/boathit/BayesianLearning/blob/master/KLDivergence.ipynb): Studying the properties of KL divergence with a Gaussian Mixture Model example.
2. [CAVI](http://nbviewer.jupyter.org/github/boathit/BayesianLearning/blob/master/CAVI.ipynb): A full example of coordinate ascent variational inference for the Gaussian Mixture Model.
3. [VAE-python](http://nbviewer.jupyter.org/github/boathit/BayesianLearning/blob/master/VAEs/VAE-python.ipynb): Variational Auto-encoder implemented in PyTorch.


## Recommended readings

* [Introducing Julia](https://en.wikibooks.org/wiki/Introducing_Julia)
* [Julia Document](https://docs.julialang.org/en/v1/)


