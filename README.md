# HumanActivityRecognition_Thesis
Human Activity Recognition, exploring different sensor-types with RealWorld HAR dataset

Author: P.C.O. Maseland
Date: 03-12-2021


![-----------------------------------------------------]
<!-- PREREQUISITES -->

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) <br>
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) <br>

<!--This project is written in Python programming language. <br>-->
The following open source packages are used in this project:
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn


![-----------------------------------------------------]
<!-- FOLDER STRUCTURE -->
    code
    .
    ├── Raw data
    |   ├── Totalset+slopes+mean+sd.csv
    ├── Data Handling
    |   ├── preprocessing.ipynb
    |   ├── batching.ipynb
    |   ├── combinging.ipynb  
    ├── Model notebooks
    |   ├── Modelling_Vanilla_Algorithms - Decision trees_Final.ipynb
    |   ├── Modelling_Vanilla_Algorithms - Multinomial Logistic Regression.ipynb  
    |   ├── CNN_Impersonal_RawData.ipynb    
    |   ├── CNN_Personal_RawData.ipynb 
    ├── Visualization_Final.ipynb
    
    
    
    <!-- :paw_prints:-->
<!-- FOLDER STRUCTURE -->
<h2 id="folder-structure"> :cactus: Folder Structure</h2>

    code
    .
    │
    ├── data
    │   ├── raw_data
    │   │   ├── phone
    │   │   │   ├── accel
    │   │   │   └── gyro
    │   │   ├── watch
    │   │       ├── accel
    │   │       └── gyro
    │   │
    │   ├── transformed_data
    │   │   ├── phone
    │   │   │   ├── accel
    │   │   │   └── gyro
    │   │   ├── watch
    │   │       ├── accel
    │   │       └── gyro
    │   │
    │   ├── feature_label_tables
    │   │    ├── feature_phone_accel
    │   │    ├── feature_phone_gyro
    │   │    ├── feature_watch_accel
    │   │    ├── feature_watch_gyro
    │   │
    │   ├── wisdm-dataset
    │        ├── raw
    │        │   ├── phone
    │        │   ├── accel
    │        │   └── gyro
    │        ├── watch
    │            ├── accel
    │            └── gyro
    │
    ├── CNN_Impersonal_TransformedData.ipynb
    ├── CNN_Personal_TransformedData.ipynb  
    ├── CNN_Impersonal_RawData.ipynb    
    ├── CNN_Personal_RawData.ipynb 
    ├── Classifier_SVM_Personal.ipynb
    ├── Classifier_SVM_Impersonal.ipynb
    ├── statistical_analysis_time_domain.py
    ├── Topological data analysis.ipynb  
