# Simple Linear Regression

This sample shows how to install and use matploblit

Run linear_reg.py in local conda environment.
```
$ conda install matplotlib
$ az ml execute start -c local linear_reg.py
```

Run linear_reg.py in a local Docker container.
```
$ az ml execute start -c docker linear_reg.py
```

Run linear_reg.py in a Docker container in a remote machine. Note you need to create/configure myvm.compute.
```
$ az ml execute start -c myvm linear_reg.py
```
