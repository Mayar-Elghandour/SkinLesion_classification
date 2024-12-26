# SkinLesion_classification
## Table of Contents
1. [Introduction](#intro)
2. [Dataset](#dataset)
     1. [MSID](#source)
     2. [MSLDv2](#structure)
     3. [Merging](#ratio)
3. [Preprocessing and Augmentation](#imp)
     1. [Preprocessing](#dataperp)
     2. [Augmentation](#class)   
4. [Feature Extratction](#result)
5. [Feature Selection](#instruction)
6. [Models](#ref)


<a name="intro"></a>
## Introduction
This project focuses on the classification of multiple cases of skin lesions from images through Machine learning algorithm, using model such as XGBoost where this dataset is mostly have been classified using Deep Learning model or Feature extraction with deep learning then classified with machine learning model

## Dataset   
The used data is a combination of 2 datasets which each represent a couple of different skin lesion images which were collected from internet-based sources:
### 1.     [Monkeypox Skin Images Dataset (MSID)](https://www.kaggle.com/datasets/dipuiucse/monkeypoxskinimagedataset)
The data consists of 770 images divided on 4 disease classes:

| Type of lesion | N. of images |
| :---: | :---: |
| MonkeyPox | 279 |
| ChickenPox | 107 |
| Measles | 91 |
| Normal | 293 |

### 2.     [Mpox Skin Lesion Dataset Version 2.0 (MSLD v2.0)](https://www.kaggle.com/datasets/joydippaul/mpox-skin-lesion-dataset-version-20-msld-v20)
This dataset includes 755 image that were gathered from a total of 541 patients. The set comprises images from six distinct classes, which are:

| Type of lesion | N. of images |
| :---: | :---: |
| MonkeyPox | 284 |
| ChickenPox | 75 |
| Measles | 55 |
| CowPox | 66 |
| HFMD | 161 |
| Normal | 114 |

### 3.     Data Merging
The datasets were each organized in a different way so they were both reorganized and merged creating a bigger data sets containing:
1. Image name
2. Image path
3. Lesion Type
4. Source (Original dataset)

After merging, the data were checked for duplicates through **Hashing algorihtm** and **Hamming distance** which helped in identifying and removing around 70 image duplications. 
AS a result, the final dataset included **1455** images.

## Preprocessing and Augmentation 


     
