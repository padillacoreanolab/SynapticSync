# SynapticSync

This repository holds code to conduct ephys analysis on data files that come from trodes and phy files. It also has code to extract behavior data from Boris and ECU data and some tools to manipulate behavioral epochs.

# Installation

```bash
pip install synapticsync
```

# How to contribute:
Clone this repository and create a new branch for your changes. 

The following commands will set up the environment you need to contribute.

```bash
cd <path/to/cloned/repository/SynapticSync>
conda env create -f environment.yml
conda activate synapticsync
poetry config virtualenvs.create false --local
poetry install
poetry run pre-commit install
```

To add a new dependency for the SynapticSync package use:
```bash
poetry add <new-package-name>
```

To add a new development specific package use:
```bash
poetry add --group dev <new-package-name>
```
