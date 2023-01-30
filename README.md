<!-- These are examples of badges you might want to add to your README:
     please update the URLs accordingly

[![Built Status](https://api.cirrus-ci.com/github/<USER>/thesis.svg?branch=main)](https://cirrus-ci.com/github/<USER>/thesis)
[![ReadTheDocs](https://readthedocs.org/projects/thesis/badge/?version=latest)](https://thesis.readthedocs.io/en/stable/)
[![Coveralls](https://img.shields.io/coveralls/github/<USER>/thesis/main.svg)](https://coveralls.io/r/<USER>/thesis)
[![PyPI-Server](https://img.shields.io/pypi/v/thesis.svg)](https://pypi.org/project/thesis/)
[![Conda-Forge](https://img.shields.io/conda/vn/conda-forge/thesis.svg)](https://anaconda.org/conda-forge/thesis)
[![Monthly Downloads](https://pepy.tech/badge/thesis/month)](https://pepy.tech/project/thesis)
[![Twitter](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter)](https://twitter.com/thesis)
-->

[![Project generated with PyScaffold](https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold)](https://pyscaffold.org/)

# Your thesis title

You should structure this template losely based on the [Data Science Cookiecutter Template](https://drivendata.github.io/cookiecutter-data-science/).

> Add a short description here!

A longer description of your project goes here...

## Setup

We generally use [conda](https://docs.conda.io/en/latest/miniconda.html) and [Jupyter notebooks](https://jupyter.org/) for development.
To set up this project, do the following:

```bash
# creates a conda environment called `thesis` from the `environment.yml` file
# ATTENTION: update the `environment.yml` as you install more packages
conda env create -f environment.yml -n thesis

# install thesis as a packages (this allows to import the code from `src` as a package called `thesis`)
pip install -e .
```

<!-- pyscaffold-notes -->

## Note

This project has been set up using PyScaffold 4.4. For details and usage
information on PyScaffold see https://pyscaffold.org/.
