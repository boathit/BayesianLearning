# Bayesian Learning

## Setup

* Install [Julia Language](https://julialang.org/) and Jupyter Notebook ([Anaconda3](https://www.anaconda.com/download/#macos))
* Install related packages in Julia REPL

    ```julia
    using Pkg

    Pkg.add("IJulia.jl")
    Pkg.add("Distributions.jl")
    Pkg.add("Optim.jl")
    Pkg.add("PyCall.jl")
    Pkg.add("PyPlot.jl")
    ```

* Run Jupyter notebook

    ```shell
    $ jupyter notebook
    ```

## Variational Inference

1. [KL Divergence](http://nbviewer.jupyter.org/github/boathit/BayesianLearning/blob/master/KLDivergence.ipynb): Studying the properties of KL divergence with a Gaussian Mixture Model example.
2. [CAVI](http://nbviewer.jupyter.org/github/boathit/BayesianLearning/blob/master/CAVI.ipynb): Coordinate ascent variational inference.


## Recommended materials

* [Introducing Julia](https://en.wikibooks.org/wiki/Introducing_Julia)
* [Julia Document](https://docs.julialang.org/en/v1/)


