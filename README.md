# DW Assignment 4: Paper Review and Algorithm Evaluation—Algorithmic Fairness
This GitHub repository contains a reproducible Python notebook and data for evaluating a bias mitigation algorithm (reweighing), which is available in the AIF360 library. To run the code, simply download the data folder and the notebook to the same directory and make sure to install the package versions specified below.
## Python and package versions
Python: 3.14.6  
aif360: 0.6.1  
pandas: 3.0.3  
numpy: 2.4.6  
scikit-learn: 1.9.0  
ucimlrepo: 0.0.7
## Data
The code uses three datasets: [Adult Census Income](https://www.kaggle.com/datasets/uciml/adult-census-income/data), [German Credit Data](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data) and [COMPAS Recidivism Racial Bias](https://www.kaggle.com/datasets/danofer/compass). The German dataset is imported from the ucimlrepo library and the other two can be found in the data folder (or downloaded from the provided links).
