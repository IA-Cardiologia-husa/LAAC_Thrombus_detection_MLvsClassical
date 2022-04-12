# Predictive power for thrombus detection after atrial appendage closure: machine learning vs. classical methods
 
This is an implementation of the experiments in the following paper which is published in REVISTA_PARA_PUBLICAR:

    Predictive power for thrombus detection after atrial appendage closure: machine learning vs. classical methods 

**In case you find the code useful, please consider giving appropriate credit to it by citing the paper above.**

    CITA

---
# Requiremetns
The code should work with [Python](https://www.python.org/) 3. It depends on some external libraries which should be installed, including:
- numpy
- pandas
- scikit-learn
- scipy
- plotnine
- warnings

A suitable [conda](https://docs.conda.io/projects/conda/en/latest/index.html) environment named LAAC_Thrombus_detection can be created and activated with:

    conda env create -f environment.yml
    conda activate LAAC_Thrombus_detection

or  install these libraries is to use pip

    pip install numpy pandas scipy scikit-learn plotnine warnings

On the other hand, the database is not available for sharing.

---
# Notebooks
In this repository we can find two notebooks:
- [Final experiments]()
- [Additional experiments]()

## FinalExperiments
In this notebook we can find the 4 experiments followed in the article. In the following workflow the 4 experiments are summarized:

![alt text](WorkFlow.jpg)


## Additional experiments
In this notebook other possibilities of experiment IV are presented varying in the model and the method of feature selection chosen.

