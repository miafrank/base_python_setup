# base_python_setup
A README that explains how to install python, pipenv, and setup a python project with virtual env

## Install Python

If you do not have Python, please install the latest 3.x version from `python.org`. You can check this by running: 

```
$ python --version
```

Alternatively you can install Python using [Homebrew](https://docs.brew.sh/Homebrew-and-Python)

```
brew install python@3.{minor_version}
```

## Install Pipenv

### Install pip 

Make sure you have pip available, you should if you are using Python downloaded from python.org.

Check this by running:

```
$ pip --version
```

If you do not have Pipenv installed already, install with [Homebrew](https://brew.sh/). [Pipenv](https://packaging.python.org/en/latest/tutorials/managing-dependencies/#managing-dependencies) is the offical package management tool reccomended by Python (similar to `npm`): 

```
$ brew install pipenv
```

Alternatively, you can install Pipenv with pip: 

```
$ pip install --user pipenv
```

## Create new project

```
$ md `/path/to/your/project`
$ cd `/path/to/your/project`

Create a new project using Python 3.{minor_version}, specifically:
$ pipenv --python 3.{minor_version}
```

## Install dependencies


```
$ pipenv install flask
```
