# Evaluating the Effect of Sample Size on Machine Learning Performance for Diabetic Neuropathy Prediction Using Real-World Clinical Data


## Overview

This repository contains the code and data associated with the research titled "_Evaluating the Effect of Sample Size on Machine Learning Performance for Diabetic Neuropathy Prediction Using Real-World Clinical Data_".

Experiments were done using Python (version 3.11.3) and the library scikit-learn (version 1.7.2). A complete list of libraries used is provided in the file `requirements.txt`.

  
## Dataset

Experiments were conducted over a publicly available dataset.[^1]

[^1]: Gulkesen, Kemal Hakan; Ülgü, Mustafa Mahir; Mutlu, Begum; Akünal, Abdullah; Ayvalı, Mustafa Okan; Akyürek, Özen; Birinci, Şuayip; Balcı, Mustafa Kemal; Sezer, Ebru (2024), “Machine Learning for Prediction of Glycemic Control in Diabetes Mellitus”, Mendeley Data, V2, doi: 10.17632/rr4rzzrjfc.2
  

## Results

According to the logistic regression analysis, 46 variables were identified as significant predictors of diabetic neuropathy. These variables are presented below:

| **Category** | **Variables** |
|---------------|---------------|
| **Demographic / Clinical** | Sex, Age, HbA1c |
| **Comorbidities** | Malignant neoplasms, Thyroid diseases, Anemia, Vitamin deficiencies, Disorders of lipoprotein metabolism and other lipidemias, Other endocrine disorders, Depression, Anxiety disorder, Retinopathies, Other eye diseases, Hypertension, Cerebrovascular diseases, Other circulatory diseases, Gastro-oesophageal reflux disease, Other digestive diseases, Musculoskeletal and connective tissue diseases, Renal failure |
| **Medications** | Other digestive drugs (e.g., vitamins, supplements, tonics, anabolic agents, appetite stimulants), Lipid-modifying agents, Genitourinary system drugs, Musculoskeletal system drugs, Antiparkinson drugs, Antipsychotics, Psychoanaleptics, Respiratory system drugs, Sensory organ drugs, Dapagliflozin, Exenatide, Gliclazide, Glimepiride, Insulin aspart, Insulin detemir, Insulin glargine, Insulin glulisine, Insulin lispro, Linagliptin, Metformin, Nateglinide, Pioglitazone, Repaglinide, Saxagliptin, Sitagliptin, Vildagliptin |

The mean are under the curve (AUC) values of the training and test sets can be found in the following file:

- `results.csv`: The AUC values of the training and test sets for each combination of sample size and feature count over 10 repetitions.

[results.csv](https://github.com/nilhanli/sample_size/blob/d520291c55513a32003d9a165c5e9b56463747fb/results.csv)

