# dModverse

R and Python packages for dynamical models: simulation with sensitivities, parameter
estimation and structural identifiability analysis.

| Package | What it does |
|---|---|
| [**dMod2**](https://github.com/dModverse/dMod2)<br><sub>R,&nbsp;C++</sub> | Parameter estimation in dynamical models: ODE models compiled with first- and second-order sensitivities, fitted by trust-region optimization with multi-start search and profile likelihood, also for mixed-effects models; PEtab and SBML exchange. Successor to [dMod](https://github.com/JetiLab/dMod). |
| [**cppDE**](https://github.com/dModverse/cppDE)<br><sub>R,&nbsp;C++</sub> | Writes, compiles and runs a C++ solver for ODEs given as equations in R, with derivatives propagated forward on dual numbers or backward by a discrete adjoint, to first and second order; the default solver backend of dMod2. |
| [**symident**](https://github.com/dModverse/symident)<br><sub>Python,&nbsp;C++</sub> | Finds the non-identifiable directions of dynamical models by Lie symmetries over finite fields, returns them as exact generators, reduces the model to identifiable parameters, and counts discrete symmetries in the parameter domain. |

## Installation

```r
# install.packages("remotes")
remotes::install_github("dModverse/cppDE")
remotes::install_github("dModverse/dMod2")
```

```sh
pip install symident
```

## Contact

Maintainer: Simon Beyer, University of Freiburg,
[simon.beyer@fdm.uni-freiburg.de](mailto:simon.beyer@fdm.uni-freiburg.de).

Please report bugs and requests for further functions as issues in the repository
concerned, or by e-mail.

dMod was created by Daniel Kaschek; dMod2 builds on its design.
