# Feature Extraction

## This repo explains how to extract feature vectors.

Data can be represented in so many formats in the field of data science, these are:

* Numerical
* Text
* Images

The scikit-learn library in python provides us with API's that can help us represent these type of data Numerically.

Data like Tmages and Text which are not numerical can be represented numerical which can be passed through our models for training and testing.

> The Libraries that are needed for this project to work are:

<code>
    pip install scikit-learn <br/>
    pip install opencv-python <br/>
    pip install numpy <br/>
    pip install matplotlib
</code>

<br/>

> You can also install all this libraries in one line

`pip install opencv-python scikit-learn numpy matplotlib`

All the codes in this project are written in the **jupyter notebook** file instead of a **python** file 

But you can look through each file install the necessary packages and run the codes needed for the algorithm to work.

#### **There are two folders in the project structure.**

1. code 
2. data

The code folder contains the code and the data folder contains the necessary files for them to work.

### This is the project structure.

```
└── Data Extraction
    ├── code
    │   ├── CategoricalAndNumericalData.ipynb
    |   ├── ImageFeatureExtraction.ipynb
    |   ├── TextFeatureExtraction.ipynb
    |
    └── data
        ├── dog.jpg
        └── exams.csv
  

```