# Randomized Optimization

## Pre-requisites
  * GT GitHub account
  * See [this document](README.md) on [jcha64/CS-7641_Randomized-Optimization](https://github.gatech.edu/jcha64/CS-7641_Randomized-Optimization/) repository
  * miniconda installed
  * Download refined data files (optionally you can find their original data files.)

### Install minicoda & make an environment to run this project.
  1. To run this project, you need to install [miniconda](https://docs.conda.io/en/latest/miniconda.html) based on your OS environment.
  2. After installing miniconda, you need to make a new environment via _**`conda env create --file environment.yaml`**_ command with [environment.yaml](environment.yaml) file.
  3. Then activate the named `AI` environment through _**`conda activate AI`**_ command.

### Processed data file
  1. You can find the revised file whcih was fined on [the previous work](https://github.gatech.edu/jcha64/CS-7641_Supervised-Learning/).
     * [wine.csv](wine.csv)

## Run various ML jobs

### Run a jupyter notebook session.
  1. Just simply run a jupyter lab session through _**`jupyter-lab`**_ command.
  2. You can run whole cells or one by one cell to follow up each ML method after loading each jupyter notebook file.
     * [A2-FlipFlop.ipynb](A2-FlipFlop.ipynb): to run various randomized optimization algorithms with the FlipFlop problem.
     * [A2-nQueens.ipynb](A2-nQueens.ipynb): to run various randomized optimization algorithms with the nQueens problem.
     * [A2-TSP.ipynb](A2-TSP.ipynb): to run various randomized optimization algorithms with the TSP (Travelling Salesman Problem).
     * [NN-randomization-v2.ipynb](NN-randomization-v2.ipynb): to run various randomized optimization methods onto [wine.csv](wine.csv) file.
