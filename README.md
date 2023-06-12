# biomarker-COVID-19-severity-recovery
Codes for analtzing the scRNA-seq data of immune cells from patients with COVID-19

In this respository, codes form analyzing the scRNA-seq data of immune cells from patients with COVID-19 are provided. These codes implement four featrue ranking algorithms: last absolute shrinkage and selection operator (LASSO), light gradient boosting ma-chine (LightGBM), Monte Carlo feature selection (MCFS), and max-relevance and min-redundancy (mRMR), and three classification algiorithms: decision tree (DT), k-nearest neighbor (kNN), and random forest.


Python environment installation
Step 1 Download the software by
git clone https://github.com/*******/*******

Step 2 Installation has been tested in Linux and Windows with Python 3 (Recommend to use Python 3.10 or miniconda 3 platform).
Since the package is written in Python 3, Python 3 with the pip tool must be installed first. The tools use the following dependencies: numpy, scipy, pandas, scikit-learn You can install these packages first, by the following commands:
pip install pandas
pip install numpy
pip install scipy
pip install scikit-learn

Step 3 cd to the software folder and run the installation command:
python *************
