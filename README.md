# python-jupyter-notebook

Here is a new python project with jupyter notebook ( or jupyter lab )


## set up

This project uses miniconda, a virtualenv and python package tool, to setup

- To install miniconda https://docs.anaconda.com/miniconda/#miniconda-latest-installer-links- after installing miniconda, we will create a virtual env called python-jupyter-notebook

- To activate this environment, use $ conda create --name python-jupyter-notebook
- To activate this environment, use $ conda activate python-jupyter-notebook
- To deactivate an active environment, use $ conda deactivate

Example

![Screenshot 2024-08-18 105801](https://github.com/user-attachments/assets/854a2ab7-52e0-45fd-a00a-18ba1cee1f51)


## Tutorial - Getting Started with Jupyter Notebooks in VS Code

https://www.youtube.com/watch?v=suAkMeWJ1yE

## useful conda commands

```
conda info --envs
conda remove -n my-env --all
conda env create -f environment.yaml -n my-env
conda env update -f environment.yaml
conda create --name python-jupyter-notebook
conda env export > environment.yaml
```

## Problem solving

### Python -1.-1.-1 in Kernel

Run `(python-jupyter-notebook) sunny@TDesktop:~/workspace/python-jupyter-notebook$ conda install iphkernel`

### The kernel failed to start as the Python Environment 'Python' is no longer available. Consider selecting another kernel or refreshing the list of Python Environments.

Run `(python-jupyter-notebook) sunny@TDesktop:~/workspace/python-jupyter-notebook$ conda install jupyter`

## Result

![Screenshot (30)](https://github.com/user-attachments/assets/72da392b-b52d-49f3-9827-63a4c1320660)


