# hello-jupyterlab

## Python

With [pyenv][] installed, run the following command in this folder to ensure that you are using the proper version of Python for this project.

```
$ pyenv install
```

[pyenv]: https://github.com/pyenv/pyenv

## Virtual Environment

The first time you use this repository, you will need to first run the following command in this folder to create a virtual environment.

```
$ python3 -m venv .environment
```

Each time you work with this repository, you will need to run the following command in this folder to activate the virtual environment.

```
$ source .environment/bin/activate
```

## pipenv

The first time you use this repository, you will need to first run the following command in this folder to install pipenv.

```
$ pipenv pip install pipenv==2024.4.1
```

Then you run the following command to install all the package dependencies.

```
$ pipenv install
```

## Jupyter Lab

Each time you work with this repository, you will need to run the following command in this folder to start JupyterLab.

```
$ jupyter lab

```
