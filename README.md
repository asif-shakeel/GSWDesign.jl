# GSWDesign.jl

GSWDesign is a Julia package which contains a fast implementation of the Gram--Schmidt Walk 
for balancing covariates in randomized experiments. 
The Gram--Schmidt Walk design allows experimenters the flexibilty to control the amount of covariate balancing.
See the references below for details of the Gram--Schmidt Walk design and its analysis.

1. Christoher Harshaw, Fredrik Savje, Daniel Spielman, Peng Zhang. "Balancing covariates in randomized experiments
using the Gram–Schmidt walk". Arxiv 1911.03071, 2019. [arxiv](https://arxiv.org/abs/1911.03071)
2. Nikhil Bansal, Daniel Dadush, Shashwat Garg, and Shachar Lovett. "The Gram–Schmidt walk: a
cure for the Banaszczyk blues". In STOC, 2018. [arxiv](https://arxiv.org/abs/1708.01079)

## Installing this package
To install this package, you must first have installed the Julia programming language.
If you have not done this, visit [julialang.org](https://julialang.org/) for instructions on how to do so.

The best way to install this package is using Julia's builtin package manager, `Pkg`. 
This package is currently unregistered and so the command for adding 
it is slightly different than for registered packages.
We discuss how to do this for Julia versions v1.0 and higher.
1. At the command line, type `julia` to enter an interactive Julia session.
2. Enter the package manager by pressing `]`.
3. To download our GSWDesign package, enter the command `add https://github.com/crharshaw/GSWDesign.jl`
4. Exit the package manager by pressing press backspace or ^C.

Now GSWDesign is installed with your version of Julia and you can use it.

## How to use this package
Once GSWDesign has been installed, you can load its functionality by including `using GSWDesign` or `import GSWDesign`
in your julia files or interactive sessions.



