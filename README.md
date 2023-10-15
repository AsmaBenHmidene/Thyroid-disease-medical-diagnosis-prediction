# Thyroid-disease-medical-diagnosis-prediction
Multiclass classification

## Objective:
To predict thyroid disease medical diagnosis

### Business problem:
   Thyroid disease is a common endocrine disorder that can affect people of all ages. It is caused by a problem with the thyroid gland, which is a small gland located in the neck. The thyroid gland produces hormones that regulate metabolism, growth, and development.

There are two main types of thyroid disease:

- Hypothyroidism occurs when the thyroid gland does not produce enough thyroid hormone.
- Hyperthyroidism occurs when the thyroid gland produces too much thyroid hormone.

Both hypothyroidism and hyperthyroidism can cause a variety of symptoms, including fatigue, weight gain or loss, changes in heart rate, and mood changes. If left untreated, thyroid disease can lead to serious health problems, such as heart disease, stroke, and infertility.

Early diagnosis and treatment of thyroid disease is important to prevent complications. However, thyroid disease can be difficult to diagnose because the symptoms are often vague and can be caused by other conditions.

In this project, we will develop a machine learning model to classify patients as having hypothyroidism, hyperthyroidism, or normal thyroid function. The model will be trained on a dataset of patient records that includes thyroid hormone levels and other clinical features.

We will use a variety of machine learning techniques, including preprocessing, feature selection, dealing with imbalanced data, modeling, and evaluation. We will also compare the performance of different machine learning algorithms and tuning parameters to develop the best possible model.

Once the model is developed, we will evaluate its performance on a held-out test set. The goal is to develop a model that is accurate and reliable, and that can be used to help diagnose thyroid disease in patients.

This project has the potential to improve the diagnosis and management of thyroid disease. By developing an accurate and reliable machine learning model, we can help clinicians identify patients with thyroid disease earlier and more accurately. This can lead to better outcomes for patients and reduce the risk of complications.

### Targeted stakeholders:
  Doctors, Hospitals, Pharmaceutical companies, Research Institutes and Ministry of Health (social aid, social health assurance, health national projects,...)

### Source of dataset:
Thyroid Data - https://archive.ics.uci.edu/ml/datasets/thyroid+disease , https://www.kaggle.com/datasets/emmanuelfwerr/thyroid-disease-data , https://www.kaggle.com/datasets/emmanuelfwerr/thyroid-disease-data

For this dataset, there are 9172 rows and 30 columns.

### Brief description of data:
The datasets featured were created by reconciling thyroid disease datasets provided by the UCI Machine Learning Repository of patient background information and blood test results along with thyroid-related medical diagnosis

- What is the target column?
target - hyperthyroidism medical diagnosis (str).

A diagnosis "-" indicates no condition requiring comment.  A diagnosis of the
form "X|Y" is interpreted as "consistent with X, but more likely Y".  The
conditions are divided into groups where each group corresponds to a class of comments.

- Letter Diagnosis: 

*hyperthyroid conditions:

A   hyperthyroid
B   T3 toxic
C   toxic goitre
D   secondary toxic

*hypothyroid conditions:

E   hypothyroid
F   primary hypothyroid
G   compensated hypothyroid
H   secondary hypothyroid

*binding protein:

I   increased binding protein
J   decreased binding protein

*general health:

K   concurrent non-thyroidal illness

*replacement therapy:

L   consistent with replacement therapy
M   underreplaced
N   overreplaced

*antithyroid treatment:

O   antithyroid drugs
P   I131 treatment
Q   surgery

*miscellaneous:

R   discordant assay results
S   elevated TBG
T   elevated thyroid hormones

## Methods
To prepare this data, the data was cleaned, and the following processes were performed:
### Exploratory Data Analysis
    - During the exploratory data analysis, boxplots and histograms were visualized for numeric datatype column. 
    - Also, barplots were visualized for categorical column. 
    - This gave a good baseline for all of the numeric and categorical columns for univariate EDA.

#### Visual 1 
![sample Figure](Figure1.png) 
