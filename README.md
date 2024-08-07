<div align="center">
<img src="https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/blob/main/images/LIFDlogo.png"></a>
<a href="https://www.cemac.leeds.ac.uk/">
  <img src="https://github.com/cemac/cemac_generic/blob/master/Images/cemac.png"></a>
  <br>
</div>

# Leeds Institute for Fluid Dynamics Machine Learning For Earth Sciences #

# Dimensionality Reduction

[![GitHub release](https://img.shields.io/github/release/cemac/LIFD_DimensionalityReduction.svg)](https://github.com/cemac/LIFD_DimensionalityReduction/releases) [![GitHub top language](https://img.shields.io/github/languages/top/cemac/LIFD_DimensionalityReduction.svg)](https://github.com/cemac/LIFD_DimensionalityReduction) [![GitHub issues](https://img.shields.io/github/issues/cemac/LIFD_DimensionalityReduction.svg)](https://github.com/cemac/LIFD_DimensionalityReduction/issues) [![GitHub last commit](https://img.shields.io/github/last-commit/cemac/LIFD_DimensionalityReduction.svg)](https://github.com/cemac/LIFD_DimensionalityReduction/commits/master) [![GitHub All Releases](https://img.shields.io/github/downloads/cemac/LIFD_DimensionalityReduction/total.svg)](https://github.com/cemac/LIFD_DimensionalityReduction/releases) ![GitHub](https://img.shields.io/github/license/cemac/LIFD_DimensionalityReduction.svg)[![DOI](https://zenodo.org/badge/366734586.svg)](https://zenodo.org/badge/latestdoi/366734586)

[![LIFD_ENV_ML_NOTEBOOKS](https://github.com/cemac/LIFD_DimensionalityReduction/actions/workflows/python-package-conda-DR.yml/badge.svg)](https://github.com/cemac/LIFD_DimensionalityReduction/actions/workflows/python-package-conda-DR.yml)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cemac/LIFD_DimensionalityReduction/HEAD?labpath=DimensionalityReduction.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cemac/LIFD_DimensionalityReduction/blob/main/LIFD_dimensionality_reduction_colab.ipynb)


This Jupyter notebook is based on Jonathan Coney's work on identifying and characterising trapped lee waves using dimensionality reduction. The work is outlined in [Coney et al., 2023](https://rmets.onlinelibrary.wiley.com/doi/full/10.1002/qj.4592). This notebook will go through the basics of [Principal Component Analysis](https://www.billconnelly.net/?p=697) and Dimensionality Reduction methods using some toy code from a Kaggle tutorial and the MNIST dataset, and then apply those methods to an Earth Science application based on Jonathan Coney's work.


## Quick look

### Quick start

**Binder and Colab buttons**

Will launch this tutorial in binder (CPU) or Google Colab (GPU)

**Running Locally**

If you're already familiar with git, Anaconda and virtual environments, the environment you need to create is found in DR.yml and the code below will install, activate and launch the notebook. The .yml file has been tested on the latest Linux, macOS and Windows operating systems.

```bash
git clone git@github.com:cemac/LIFD_DimensionalityReduction.git
cd LIFD_DimensionalityReduction
conda env create -f DR.yml
conda activate DR
jupyter-notebook
```

## Installation and Requirements

This notebook is designed to run on a laptop with no special hardware required. Therefore, it is recommended to do a local installation as outlined in the repository [howtorun](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/howtorun.md) and [jupyter_notebooks](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/jupyter_notebooks.md) sections.


# Licence information #

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">LIFD_ENV_ML_NOTEBOOKS</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://cemac.leeds.ac.uk/" property="cc:attributionName" rel="cc:attributionURL">cemac</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Acknowledgements

Thanks to Jonathan Coney for the basis of this tutorial. This tutorial is part of the [LIFD ENV ML NOTEBOOKS](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS) series. Please refer to the parent repository for full acknowledgements.
