# Evaluating the Effect of Sample Size on Machine Learning Performance for Diabetic Neuropathy Prediction Using Real-World Clinical Data


## Overview

This repository contains the code and data associated with the research titled "_Evaluating the Effect of Sample Size on Machine Learning Performance for Diabetic Neuropathy Prediction Using Real-World Clinical Data_".

Experiments were done using Python (version 3.11.3) and the library scikit-learn (version 1.7.2). A complete list of libraries used is provided in the file `requirements.txt`.

  
## Dataset

Experiments were conducted over a publicly available dataset.[^1]

[^1]: Gulkesen, Kemal Hakan; Ülgü, Mustafa Mahir; Mutlu, Begum; Akünal, Abdullah; Ayvalı, Mustafa Okan; Akyürek, Özen; Birinci, Şuayip; Balcı, Mustafa Kemal; Sezer, Ebru (2024), “Machine Learning for Prediction of Glycemic Control in Diabetes Mellitus”, Mendeley Data, V2, doi: 10.17632/rr4rzzrjfc.2
  

## Results

According to the logistic regression analysis, 46 variables were found to be significant predictors of diabetic neuropathy, as follows: sex, age, HbA1c, malignant neoplasms, thyroid diseases, anemia, vitamin deficiencies, disorders of lipoprotein metabolism and other lipidemias, other endocrine disorders, depression, anxiety disorder, retinopathies, other eye diseases, hypertension, cerebrovascular diseases, other circulatory diseases, gastro-oesophageal reflux disease, other digestive diseases, musculoskeletal and connective tissue diseases, renal failure, other digestive drugs (e.g., vitamins, supplements, tonics, anabolic agents, appetite stimulants), lipid-modifying agents, genitourinary system drugs, musculoskeletal system drugs, antiparkinson drugs, antipsychotics, psychoanaleptics, respiratory system drugs, sensory organ drugs, dapagliflozin, exenatide, gliclazide, glimepiride, insulin aspart, insulin detemir, insulin glargine, insulin glulisine, insulin lispro, linagliptin, metformin, nateglinide, pioglitazone, repaglinide, saxagliptin, sitagliptin, vildagliptin.

The mean are under the curve (AUC) values of the training and test sets can be found in the following file:

- `results.csv`: The AUC values of the training and test sets for each combination of sample size and feature count over 10 repetitions.

[results.csv](https://github.com/nilhanli/sample_size/blob/d520291c55513a32003d9a165c5e9b56463747fb/results.csv)

