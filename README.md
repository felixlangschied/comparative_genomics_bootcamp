# Welcome to the Comparative Genomics Bootcamp!


* In this tutorial, we will go through an example analysis that will teach you basic tools in comparative genomics and many other sequence-based areas of bioinformatics.

* Before we start, this tutorial will assume that you are familiar with the Bash shell that is used to navigate Linux-based environments. If you need a crash course, take a look at this **[Bash Bootcamp](http://korflab.ucdavis.edu/bootcamp.html)** by Keith Bradnam.

* This tutorial will be presented in the format of multiple [Jupyter Notebooks](https://jupyter.org/). In principle, you don't need to know any programming languages to follow this tutorial. However, a basic knowledge of any general purpose language like Python will help you with many downstream analyses of your results. If you want to get started with Python, here is a great **[free tutorial for python](https://github.com/burkesquires/python_biologist/tree/master)** by Burke Squires. 

## Setting up your computer environment

### For Windows users

Many tools used in Bioinformatics are only available in GNU/Linux environments (including MacOS). Windows users should therefore follow this tutorial using a Windows Subsystem for Linux (WSL), for example with the **[Ubuntu for Windows](https://ubuntu.com/desktop/wsl)** distribution.

### Mamba

<img src="docs/mamba_logo.png" width="300"/>

[Mamba](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html) is fast and lightweight version of the popular [Anaconda](https://www.anaconda.com/) package manager. You can install most packages with Anaconda and therefore also with Mamba. Whenever you see a `conda` command in the installation instructions of a package, just use the `mamba` keyword instead to make the installation faster.

- Step 1: If not already present, install Mamba on your computer system following **[these instrucions](https://anaconda.org/conda-forge/mamba)**
- Step 2: Open a terminal and navigate to this directory with the `enironment.yml` file
- Step 3: Create a Mamba environment that creates all the packages that you need for this tutorial: `mamba env create -n cg_bootcamp -f environment.yml`
- Step 4: Activate the environment: `mamba activate cg_bootcamp`
