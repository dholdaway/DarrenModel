OasisLMF model repository (OM)
============================================================================================================================

[![Build Status](https://ci.oasislmfdev.org/buildStatus/icon?job=OasisLMF_om/master)](https://ci.oasislmfdev.org/view/Oasis/job/OasisLMF_om/job/master/)

# DarrenModel

Oasis Model

## Cloning the repository

You can clone this repository by running `git clone https://github.com/OasisLMF/DarrenModel.git`
or directly download as a [zip file](https://github.com/OasisLMF/DarrenModel/archive/master.zip)

## Running via the Oasis MDK

The <a href="https://pypi.org/project/oasislmf/" target="_blank">Oasis model development kit (MDK)</a> is a Python package which provides a command line interface (CLI) for developing and running models using the Oasis framework. It can be installed via the Python package installer `pip` (or `pip3` for Python 3). This repository contains a <a href="https://github.com/OasisLMF/DarrenModel/blob/master/oasislmf.json" target="_blank">JSON configuration file</a> that allows the model to be run via the MDK.

**Python package Install**
```
pip install oasislmf
```

Using the configuration file an end-to-end analysis can be executed using the command:

	oasislmf model run -C oasislmf.json

Files will be generated by default in a UTC timestamped folder named `runs/losses-<UTC timestamp`> in your working directory.

