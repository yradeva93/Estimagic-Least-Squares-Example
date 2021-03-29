# Estimagic-Least-Squares-Example
This repository contains a Jupyter Notebook that complements a Pull Request to [estimagic](https://github.com/OpenSourceEconomics/estimagic).

The PR adds two algorithms from the [scipy.optimize.least_squares](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.least_squares.html#r20fc1df64af7-jjmore) optimizer, namely `scipy_ls_trf` and `scipy_ls_dogbox`. 

The Notebook is used as a supplementary material for assessment for the course [OSE: Scientific Computing](https://ose-scientific-computing.readthedocs.io/en/latest/iteration/lecture_plan_2020.html), Winter Semester 2020/21, Univesity of Bonn by [Prof. Philipp Eisenhauer](https://peisenha.github.io/) within the [Open Source Economics Innitiative](https://open-econ.org/).

## Usage
In order to use this Notebook, you need to install the estimagic [fork](https://github.com/yradeva93/estimagic).

The fork is added as a submodule to this repository.

To do install the estimagic fork, run:

```bash
# Clone recursive to also fetch the submodule
git clone --recursive https://github.com/yradeva93/Estimagic-Least-Squares-Example
# Change into fork's subdirectory
cd Estimagic-Least-Squares-Example/estimagic
# Install environment
conda env create -f environment.yml
conda activate estimagic
pip install -e .
# Go to Notebook directory
cd ..
# Run jupyter
jupyter notebook
```

Your default web browser with the loaded Notebook should open now.
