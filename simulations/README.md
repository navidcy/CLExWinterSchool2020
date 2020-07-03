# Simulations

This folder contains Jupyter notebooks that reproduce the animations used in the presentation. The Jupyter notebooks run [Julia](https://www.julialang.org) (which, by the way, happens to be the "Ju" in Jupyter).

- `twodnavierstokes_decaying.ipynb`: Simulation of decaying 2D turbulence on a doubly-periodic domain. 
- `barotropicqg_betadecay.ipynb`: Simulation of decaying barotropiq quasi-geostrophic turbulence on a beta-plane. 

To run the notebooks locally you would need to [install Julia](https://www.julialang.org/downloads/) on your machine. Afterwards you need to install the [`IJulia` package](https://github.com/JuliaLang/IJulia.jl) so that Jupyter notebooks can run Julia. This is done simply by calling `using Pkg; Pkg.add("IJulia")` within the Julia REPL.

Alternatively, you can run the notebooks online via Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/navidcy/CLExWinterSchool2020/master)