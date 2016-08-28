Tensorflow Installation
======

Steps to install tensorflow using conda

1. Install anaconda
2. Create conda environment called tensorflow: `conda create -n tensorflow python=3.5`
3. Run: `source activate tensorflow` and `conda install -c conda-forge tensorflow` 
4. ... use tensorflow after installation
5. ... use conda to install other packages library, eg: `conda install nltk`
6. When you are done using Tensorflow, deactivate the environment: `source deactivate`

Read more about: [conda vs. pip vs. virtualenv](http://conda.pydata.org/docs/_downloads/conda-pip-virtualenv-translator.html)

At the glance: Pip is a package manager, and Virtualenv is an environment manager. Conda is both.

DeepQA Installation
=========

The program require the following dependecies (easy to install using conda):

* python 3
* tensorflow (tested with v0.9.0)
* numpy: already included in python 3
* CUDA (for using gpu, see TensorFlow installation page for more details)
* nltk: 
* tqdm (for the nice progression bars)
* The Cornell dataset is already included.


