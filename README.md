# BIOMD0000000102: Legewie2006_apoptosis_WT

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000102.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000102.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000102 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


The model reproduces active Caspase-3 time profile corresponding to the total
Apaf-1 value of 20 nM as depicted in Fig 2-A . The model was successfully
tested on MathSBML.


