# SkinLesion_classification
## Table of Contents
1. [Introduction](#intro)
2. [Dataset](#dataset)
     1. [Data source](#source)
     2. [Data structure](#structure)
     3. [Data proportions](#ratio)
3. [Implementation](#imp)
     1. [data preparation](#dataperp)
     2. [data preprocessing](#class)
     3. [feature extraction](#ex)
4. [Results](#result)

5. [Instructions](#instruction)
6. [References](#ref)
7. [Kaggle Datasets](#kdataset)
8. [Kaggle Notebooks](#knote)


<a name="intro"></a>
## Introduction
This project focuses on the classification of multiple cases of skin lesions from images through Machine learning algorithm, using model such as XGBoost where this dataset is mostly have been classified using Deep Learning model or Feature extraction with deep learning then classified with machine learning model

## Dataset Description  
The used data is a combination of 2 datasets which each represent a couple of different skin lesion images which were collected from internet-based sources:
### 1.     [Monkeypox Skin Images Dataset (MSID)](https://www.kaggle.com/datasets/dipuiucse/monkeypoxskinimagedataset)
The data consists of 770 images divided on 4 disease classes:

| Type of lesion | N. of images |
| :---: | :---: |
| 'MonkeyPox' | 279 |
| 'ChickenPox' | 107 |
| 'Measles' | 91 |
| 'Normal' | 293 |

### 2.     [Mpox Skin Lesion Dataset Version 2.0 (MSLD v2.0)](https://www.kaggle.com/datasets/joydippaul/mpox-skin-lesion-dataset-version-20-msld-v20)
This dataset includes 755 image that were gathered from a total of 541 patients. The set comprises images from six distinct classes, which are:

| Type of lesion | N. of images |
| :---: | :---: |
| 'MonkeyPox' | 284 |
| 'ChickenPox' | 75 |
| 'Measles' | 55 |
|'CowPox'|66|
|HFMD|161|
| 'Normal' | 114 |



     
