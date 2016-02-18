# FLASH

## What is FLASH?

FLASH is a package to perform Bayesian optimization on tuning data analytic pipelines. Specifically, it is a two-layer Bayesian optimization framework, which first uses a parametric model to select promising algorithms, then computes a nonparametric model to fine-tune hyperparameters of the promising algorithms. FLASH is licensed under the GPL license.

## Installation

FLASH is developed on top of [HPOlib](http://www.automl.org/hpolib.html), a general platform for hyperparameter optimization. Since HPOlib was developed on Ubuntu and currently only supports Linux distributions, FLASH also only works on Linux (we developed and tested our package on Ubuntu).

1) Clone the package
```bash
git clone https://github.com/yuyuz/FLASH.git
```

2) Install conda
```bash
wget https://repo.continuum.io/miniconda/Miniconda-latest-Linux-x86_64.sh
bash Miniconda-latest-Linux-x86_64.sh
```

3) Install dependencies
```bash
easy_install -U distribute
conda install -y numpy scipy matplotlib scikit-learn==0.16.1
pip install hyperopt liac-arff
```

4) Install package
```bash
cd /path/to/FLASH
python setup.py install
```

## Benchmark Datasets

http://www.cs.ubc.ca/labs/beta/Projects/autoweka/datasets/

## Benchmark Pipeline

## How to Run?

## 
