# HumanActivityRecognition_Thesis
Human Activity Recognition, exploring different sensor-types with RealWorld HAR dataset

Author: P.C.O. Maseland
Date: 03-12-2021


<h2 id="prerequisites"> Prerequisites</h2>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) <br>
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) <br>

<!--This project is written in Python programming language. <br>-->
The following open source packages are used in this project:
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn


<h2 id="folder-structure">Folder Structure</h2>
In data handling file notebooks can be found for preparing the data before modeling it. This follows the structure of 1. data preperation for acc, gyr and mag sensors. 2. Combining these three sets. 3. Creating batches and extract features. Also preperation of other sensors can be found here, although they are not used for modelling. <br>

Further, in Data folder, a google drive link to the Totalset+slopes+mean+sd.csv file can be found that is used for modelling. <br>

At last in the model notebooks folder all notebooks neccesary for feature selection, gridsearch and modelling of DT, MLR and RF can be found.

    code
    .
    ├── Data Handling
    |   ├── 1.Data Preperation_Final.ipynb
    |   ├── 2.Combined Dataset_Final.ipynb
    |   ├── 3.Batches_Feature Extraction_Final.ipynb
    |   ├── _Data Preperation-GPS.ipynb
    |   ├── _Data Preperation-Light.ipynb
    |   ├── _Data Preperation-Mic.ipynb
    |
    ├── Data
    |   ├── Totalset+slopes+mean+sd.csv
    |
    ├── Model notebooks
    |   ├── Modelling_Vanilla_Algorithms - Decision tree_Final.ipynb
    |   ├── Modelling_Vanilla_Algorithms - Feature Selection_Final.ipynb 
    |   ├── Modelling_Vanilla_Algorithms - Gridsearch MLR_Final.ipynb    
    |   ├── Modelling_Vanilla_Algorithms - Gridsearch RF_Final.ipynb 
    |   ├── Modelling_Vanilla_Algorithms - Multinomial Logistic Regression_Final.ipynb 
    |   ├── Modelling_Vanilla_Algorithms - RandomForest_Final.ipynb
    |
    ├── Visualization_Final.ipynb
    
    
