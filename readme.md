# Arbor Tutorial for [NEST Conference 2024](https://nest-simulator.org/conference-2024)

This tutorial take you from the bare bones concepts of bio-physically detailled
cells to a simple network in Arbor. It is meant mainly for self-directed study
and experimentation with the opportunity to ask questions. If you are tackling
this on your own (i.e. not during a workshop), please contact us on [Gitter](https://app.gitter.im/#/room/#arbor-tutorial:gitter.im).

## Getting Started

The easiest way to run this tutorial is installation-free on the EBRAINS platform. You can open an account with your institutional email address for free and then start the tutorial here:

[![](https://nest-simulator.org/TryItOnEBRAINS.png)](https://lab.ebrains.eu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fthorstenhater%2Farbor-tutorial&urlpath=lab%2Ftree%2Farbor-tutorial%2Farbor-tutorial.ipynb&branch=main)

Aternatively you can install all dependencies on your own system manually.
You'll need recent versions of Linux or MacOS, Python3, and possibly a C++ compiler.
Start by cloning this repository and then open a shell:

```bash
python3 -m venv venv
source venv/bin/activate
pip3 install arbor numpy seaborn matplotlib networkx jupyter
jupyter lab
```

While your packages are being installed, you can take a look at the introduction
in <intro.pdf>. Then, open the <arbor-tutorial.ipynb> notebook; everything else
should follow from there.

## Useful Links
- Source code :: https://github.com/arbor-sim/arbor/
- Documentation :: https://docs.arbor-sim.org/en/stable/
- Chat server :: https://app.gitter.im/#/room/#arbor-sim_community:gitter.im
- This :: https://github.com/thorstenhater/arbor-tutorial
