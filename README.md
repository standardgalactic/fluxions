# Fluxions

## CS207 Final Project Group 10 [![Build Status](https://travis-ci.com/CS207-Final-Project-Group-10/cs207-FinalProject.svg?branch=master)](https://travis-ci.com/CS207-Final-Project-Group-10/cs207-FinalProject.svg?branch=master) [![Coverage Status](https://coveralls.io/repos/github/CS207-Final-Project-Group-10/cs207-FinalProject/badge.svg)](https://coveralls.io/github/CS207-Final-Project-Group-10/cs207-FinalProject?branch=master) [![Documentation Status](https://readthedocs.org/projects/fluxions/badge/?version=latest)](https://fluxions.readthedocs.io/en/latest/?badge=latest)



## Group Members:

- **William C. Burke**
- **Nathan Einstein**
- **Michael S. Emanuel**
- **Daniel Inge**

----

## Documentation

The documentation can be found [here](https://fluxions.readthedocs.io/en/latest/index.html#)
   
## Installation Instructions 
- #### For end users:
Our package is available on PyPI. Before installing ensure you have a Python3 environment with numpy installed available.

If you are using a Mac you can setup an appropriate virtual environment in your desired directory as follows:

```console
pip3 install virtualenv
virtualenv -p python3 venv
source venv/bin/activate

pip3 install numpy
```

Once you have an appropriate environment set up, you can install the fluxions package with the following command:

```console
pip3 install fluxions
```
- #### For developers:

Clone the [git repository](https://github.com/CS207-Final-Project-Group-10/cs207-FinalProject) to a location of your choice.

Ensure you have a Python3 environment available. If you want to use a virtual environment, execute the following code in the cloned directory:

```console
pip3 install virtualenv
virtualenv -p python3 venv
source venv/bin/activate
```

Finally install the requirements:

```console
pip3 install -r requirements.txt
```

We use pytest for testing. In order to run the tests, execute the following from the root of the cloned directory:

```console
pytest fluxions/
```
