This repository contains the code needed to reproduce the analyses found within

**Spanish-language text classification for conservation evidence synthesis using multi-lingual pre-trained models**

All analysis was conducted using Python 3.13.3
An overview of the scripts and a list of the packages used can be found at the bottom of this page.

Data requirements
Before running any code files, please download the relevant text data.
The links below provide access to the data.

Figures relevant to the manuscript can be found in the results folder.
Large results are available in the links below due to their size.

**Overview of scripts**

1.pre_process_main_text - Pre-process raw data. Download Raw Data to run this script.
2.feature_engineering - Remove stopwords, unwanted characters, lemmatize. Use the output of script 1 to run this script.
3.model_training - Train all model variants. Use the output of script 2 to run this script.
4.best_model_svm_12 -  Train model, error analysis, explainable AI with SHAP values. Download Clean Data to run this script.
4.best_model_svm_24 -  Train model, error analysis, explainable AI with SHAP values. Download Clean Data to run this script.
4.best_model_svm_36 -  Train model, error analysis, explainable AI with SHAP values. Download Clean Data to run this script.
4.best_model_svm_42 -  Train model, error analysis, explainable AI with SHAP values. Download Clean Data to run this script.
5.visualisation - Create heatmap. Use model scores csv (output of any script 4) to reproduce this. 

**Data requirements**

Raw Data:https://doi.org/10.6084/m9.figshare.29126096
Processed Data: 
Clean Data: https://doi.org/10.6084/m9.figshare.29036840

**Library requirements**

embetter[text]==0.6.4
fasttext==0.9.3
fasttext-wheel
imbalanced-learn==0.12.0
imblearn==0.0
Levenshtein==0.21.1
matplotlib==3.7.2
matplotlib-inline==0.1.7
mpu==0.23.1
nltk==3.8.1
numpy==1.26.4
pandas==2.0.2
pyarrow==20.0.0
polars==1.30.0
regex==2023.6.3
scikit-learn==1.3.0
scipy==1.12.0
spacy==3.5.4
seaborn==0.13.0
sentence-transformers==2.3.1
sentencepiece==0.1.99
shap==0.46.0
shapely==2.0.6
stop-words==2018.7.23
stopwords==1.0.0
tokenize-rt==5.1.0
tokenizers==0.20.1
torch==2.5.1
transformers==4.45.2
wordcloud==1.9.3

**Results**

https://figshare.com/s/74145a9cf53329b69bd7 
https://figshare.com/s/74145a9cf53329b69bd7
https://figshare.com/s/0fa0886ef5734a77893c
