# Day 1
The main goal of the day is to familiarize with python language and python standard libray.

## Create a conda environment for today

```bash
conda install -n day1 -c conda-forge python=3.10 jupyter
```
Optional if you want to follow the slides interactively
```bash 
conda install -n day1 -c conda-forge python=3.10 jupyter jupyter_contrib_nbextensions rise
```

```bash
conda activate day1
jupyter nbextension enable splitcell/splitcell
```

## Start the notebook
With your `day1` environment activated type
```bash
jupyter-notebook
```