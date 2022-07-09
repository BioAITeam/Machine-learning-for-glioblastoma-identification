# Machine learning applications on intratumoral heterogeneity in glioblastoma using single-cell RNA-Seq data
Artificial Intelligence (AI) is revolutionizing all fields that affect people's lives and health. One of the most critical applications is in the study of tumors. It is the case of glioblastoma (GBM) that has behaviors that need to be understood to develop effective therapies. Due to advances in single-cell RNA sequencing, it is possible understanding the cellular and molecular heterogeneity in the GBM. Given that there are different cell groups in these tumors, there is a need to apply Machine Learning (ML) algorithms. It will allow extracting information to understand how cancer changes and broaden the search for effective treatments. We proposed multiple comparisons of ML algorithms to classify cell groups based on GBM RNA-Seq data. This broad comparison spectrum can show the scientific-medical community which models can achieve the best performance in this task. In this work are classified the following cell groups: Tumor Core (TC), Tumor Periphery (TP), and Normal Periphery (NP), in binary and multi-class scenarios. This work presents the biomarkers found for the models with the best results. The literature extensively supports the study and allows the comparison with the findings of this work. We proposed a methodology including a large set of ML algorithms to discriminate between GBM cell groups. The results presented here allow us to verify the biomarkers to understand the genetic characteristics of GBM, which may be affected by a suitable identification of GBM heterogeneity. This work obtained for the four scenarios covered cross-validation results of 93.03±5.37%, 97.42±3.94%, 98.27±1.81% and 93.04±6.88% for classification of TP versus TC, TP versus NP, NP versus TP and TC (TPC), and NP versus TP versus TC, respectively. 

## Citing

If you use our project for your research or if you find this paper and repository helpful, please consider citing the work.

## Folders

- **Data** This folder contain the dataset. Unzip the "zip" file when you download or clone the repository to get the dataset.
- **Notebooks** In this folder, you will find all algorithms and implementations for the dataset. 

## Requirements
This repository was developed in the Python 3 (3.8) programming language.

## Package installation

We highly recommend to use and install Python packages within an Anaconda environment. To create, execute the command below:
```
conda update -n base -c defaults conda
```
```
conda create --name GBM python=3.8
```
```
pip install notebook
```
So, activate it:
```
conda activate GBM
```
Now, install the libraries
```
pip install anaconda keras-gpu
```
```
pip install yellowbrick
```
```
pip install opencv-python
```
```
pip install scikit-image
```
```
pip install pandas
```
```
pip install pydot
```
```
pip install graphviz
```
```
pip install seaborn
```
```
pip install dtreeviz
```
```
pip install imblearn
```
```
pip install statsmodels
```
```
pip install seaborn
```
```
pip install dtreeviz
```
```
pip install imblearn
```
```
pip install statsmodels
```
```
pip install tqdm
```
```
pip install xgboost
```
```
pip install bokeh
```
```
conda install jupyter 
```


## Execution
After installing all the Requirements, you must clone the repository using.
```
git clone https://github.com/BioAITeam/Machine-learning-for-glioblastoma-identification.git
```
Enter the cloned folder, then open the folder and run the notebooks.

If you will use Google Colab, upload the cloned folder to Google Drive, then open the folder and run the notebooks.
