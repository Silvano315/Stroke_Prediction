# Stroke_Prediction

1. [Introduction](#introduzione)
2. [Dataset](#sezione-1)
    - [Kaggle](#sottosezione-11)
    - [Description](#sottosezione-12)
3. [Methods](#sezione-2)
    - [Workflow](#sottosezione-21)
    - [Exploratory Data Analysis](#sottosezione-22)
    - [Machine Learning models](#sottosezione-23)
    - [eXplainable Artificial Intelligence](#sottosezione-24)
4. [Results](#sezione-3)
    - [ML prediction](#sottosezione-31)
    - [SHAP analysis](#sottosezione-32)
5. [Conclusions](#sezione-4)
6. [References](#sezione-5)

## Introduction

Stroke is a brain attack. It occurs when either blood flow is obstructed in a brain region (ischemic stroke) or sudden bleeding in the brain (hemorrhagic stroke). The effects can lead to brain damage with loss of vision, speech, paralysis and, in many cases, death. 
According to the World Health Organization (WHO)[[1](#ref1)], annually, 15 million people worldwide suffer a stroke. 5 million die and another 5 million are left permanently disabled. An important information also for this project is that stroke can occur in about 8% of children.
In [[2](#ref2)], the World Stroke Organization (WSO) states that stroke continues to be the second-leading cause of death and the third-leading cause of death and disability combined in the world. 
[[3](#ref3)] have made a systematic analysis about global, regional, and national burden of disorders affecting the nervous system and have found that, among 37 conditions affecting the nervous system, stroke is the leading group cause of Disability-adjusted life-years (DALYs) in 2021 for both adults aged 20–59 years, adults aged 60–79 years and adults aged 80 years and older.

## Dataset

### Kaggle
The dataset used for this project comes from Kaggle at this link [[4](#ref4)] and it is stored in [raw_data](Stroke_Prediction/raw_data). This dataset is a csv file and it contains 5110 rows and 12 columns, which are:
- id: unique identifier
- gender: "Male", "Female" or "Other"
- age: age of the patient
- hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- ever_married: "No" or "Yes"
- work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
- Residence_type: "Rural" or "Urban"
- avg_glucose_level: average glucose level in blood
- bmi: body mass index
- smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
- stroke: 1 if the patient had a stroke or 0 if not

### Description
[TO DO] General description about this dataset, number of patients and features.

## Methods

### Workflow
[TO DO] An image of the workflow about all the methods used.

### Exploratory Data Analysis

### Machine Learning models

### eXplainable Artificial Intelligence

## Results

### ML prediction

### SHAP analysis

## Conclusions

## References

1. <a name="ref1"></a> https://www.emro.who.int/health-topics/stroke-cerebrovascular-accident/index.html
2. <a name="ref2"></a> https://pubmed.ncbi.nlm.nih.gov/34986727/
3. <a name="ref3"></a> https://www.thelancet.com/journals/laneur/article/PIIS1474-4422(24)00038-3/fulltext
4. <a name="ref4"></a> https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data

