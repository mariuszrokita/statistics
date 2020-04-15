# statistics

# Getting started

## Virtual environment

```shell
conda create --name statistics python=3.7 jupyter jupyterlab
conda activate statistics
```

## Install dependencies

```shell
pip install --upgrade pip
pip install -r requirements.txt
```

It is also worth installing the Jupyter Notebook Extensions:

```shell
pip install jupyter_contrib_nbextensions && jupyter contrib nbextension install
```