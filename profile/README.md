# dModverse

R and Python packages for ODE models of biochemical reaction networks: simulation with
sensitivities, parameter estimation and structural identifiability analysis.

| Package | What it does |
|---|---|
| [**dMod2**](https://github.com/dModverse/dMod2)<br><sub>R</sub> | Models, objectives, optimisers and profile likelihoods for ODE models; PEtab import and export. Successor to [dMod](https://github.com/JetiLab/dMod). |
| [**cppDE**](https://github.com/dModverse/cppDE)<br><sub>R,&nbsp;C++</sub> | Generated C++ for ODE integration with forward and reverse sensitivities to second order, events and switches; the backend of dMod2. |
| [**symident**](https://github.com/dModverse/symident)<br><sub>Python,&nbsp;C++</sub> | Structural identifiability by Lie symmetries over finite fields, with reduction to identifiable parameters. [Documentation](https://dmodverse.github.io/symident/) |

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
