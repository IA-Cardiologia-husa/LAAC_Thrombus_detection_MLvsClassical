## Predictive power for thrombus detection after atrial appendage closure: machine learning vs. classical methods

[![DOI](https://zenodo.org/badge/480768705.svg)](https://zenodo.org/badge/latestdoi/480768705)

This repo provides code for the research article *Predictive power for thrombus detection after atrial appendage closure: machine learning vs. classical methods*

The aim of this article is to determine whether any differences exist with respect to the predictive power between the classical multivariable methodology and the machine learning one to predict thrombus after atrial appendage closure. Secondarily, we extract the predictor variables of both methodologies and analyze their differences.
 
### Notebooks:

- [Reported experiments](https://github.com/IA-Cardiologia-husa/LAAC_Thrombus_detection_MLvsClassical/blob/main/Final_experiments.ipynb)

![Experiment workflow](WorkFlowNotebook.png "Experiments workflow")

- [Additional experiments](https://github.com/IA-Cardiologia-husa/LAAC_Thrombus_detection_MLvsClassical/blob/main/Additional_experiments.ipynb)

---
# Requirements

Programming language: [Python 3](https://www.python.org/).

Dependencies:
- numpy
- pandas
- scikit-learn
- scipy
- plotnine
- warnings

A suitable [conda](https://docs.conda.io/projects/conda/en/latest/index.html) environment named LAAC_Thrombus_detection can be created and activated with:

    conda env create -f environment.yml
    conda activate LAAC_Thrombus_detection

otherwise

    pip install numpy pandas scipy scikit-learn plotnine warnings

