This repository contains the code needed to reproduce the analyses found within

**Spanish-language text classification for conservation evidence synthesis using multi-lingual pre-trained models**

All analysis was conducted using Python 3.13.3< br / >
An overview of the scripts and a list of the packages used can be found at the bottom of this page.< br / >

Data requirements< br / >Before running any code files, please download the relevant text data.< br / >
The links below provide access to the data.< br / >

Figures relevant to the manuscript can be found in the results folder.< br / >
Large results are available in the links below due to their size.< br / >

**Overview of scripts**

1.pre_process_main_text - Pre-process raw data. Download Raw Data to run this script.< br / >
2.feature_engineering - Remove stopwords, unwanted characters, lemmatize. Use the output of script 1 to run this script.< br / >
3.model_training - Train all model variants. Use the output of script 2 to run this script.< br / >
4.best_model_svm_12 -  Train model, error analysis, explainable AI with SHAP values. Download Clean Data to run this script.< br / >
4.best_model_svm_24 -  Train model, error analysis, explainable AI with SHAP values. Download Clean Data to run this script.< br / >
4.best_model_svm_36 -  Train model, error analysis, explainable AI with SHAP values. Download Clean Data to run this script.< br / >
4.best_model_svm_42 -  Train model, error analysis, explainable AI with SHAP values. Download Clean Data to run this script.< br / >
5.visualisation - Create heatmap. Use model scores csv (output of any script 4) to reproduce this.< br / >

**Data requirements**

Raw Data:https://doi.org/10.6084/m9.figshare.29126096< br / >
Processed Data:< br / > 
Clean Data: https://doi.org/10.6084/m9.figshare.29036840< br / >

**Library requirements**

embetter[text]==0.6.4< br / >
fasttext==0.9.3< br / >
fasttext-wheel< br / >
imbalanced-learn==0.12.0< br / >
imblearn==0.0< br / >
Levenshtein==0.21.1< br / >
matplotlib==3.7.2< br / >
matplotlib-inline==0.1.7< br / >
mpu==0.23.1< br / >
nltk==3.8.1< br / >
numpy==1.26.4< br / >
pandas==2.0.2< br / >
pyarrow==20.0.0< br / >
polars==1.30.0< br / >
regex==2023.6.3< br / >
scikit-learn==1.3.0< br / >
scipy==1.12.0< br / >
spacy==3.5.4< br / >
seaborn==0.13.0< br / >
sentence-transformers==2.3.1< br / >
sentencepiece==0.1.99< br / >
shap==0.46.0< br / >
shapely==2.0.6< br / >
stop-words==2018.7.23< br / >
stopwords==1.0.0< br / >
tokenize-rt==5.1.0< br / >
tokenizers==0.20.1< br / >
torch==2.5.1< br / >
transformers==4.45.2< br / >
wordcloud==1.9.3< br / >

**Results**

https://figshare.com/s/74145a9cf53329b69bd7< br / >
https://figshare.com/s/74145a9cf53329b69bd7< br / >
https://figshare.com/s/0fa0886ef5734a77893c< br / >
