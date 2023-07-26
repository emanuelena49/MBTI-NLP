# An analysis of MBTI types using NLP techniques
#### Advanced Data Science - NLP Exam Project

*Emanuele Lena*

## Introduction

### Goals

The purpose of this project is to analyze the descriptions of the **Myers-Briggs Type Indicator (MBTI) 16 psychological types** using *Natural Language Processing (NLP)* and data science techniques.

The actual goals of the project are two:

1. first, we want to see if NPL techniques can be used to extract information, traits and similarities between the types;

2. secondly, we want to see if in the overall description of the types there is some kind of emergent structure, and if this structure follows the proposed MBTI dichotomies or not.

Used methods include:

- sentence scoring-based summarization (frequency and TF-IDF);
- clustering on TF-IDF vectors using K-Means
- PCA
- POS tagging and clustering just on some parts of speech
- topic modelling using LDA

### Notebooks

Concretely, in the project (main Jupyter notebook: [mbti_types.ipynb](./mbti_types.ipynb)) we will:

- explore the textual descriptions of the 16 MBTI types, using summarization techniques to extract brief summaries and discriminant traits of;
- use clustering and PCA to look for similarities and groupings between the types;
- use topic modelling to look for latent features in the descriptions;

In a secondary notebook ([mbti_twitter.ipynb](./mbti_types_classification.ipynb)) there is a naive attempt to classify the MBTI types of some twitter users, (using simple *bag-of-words* approaches). This is just a (not so successful) experiment, and it is not the main focus of the project.

## Install and use the notebooks

All the project dependencies and virtual enviroments are managed using `poetry`. 