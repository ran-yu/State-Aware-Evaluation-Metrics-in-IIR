# State-Aware-Meta-Evaluation-of-Evaluation-Metrics-in-IIR
This repository contains external resource for paper: Jiqun Liu, Ran Yu. State-Aware Meta-Evaluation of Evaluation Metrics in Interactive Information Retrieval. CIKM 2021.

## query_state_annotation.csv
contains state annotation of queries.
Columns:
- **id** contains query ID as in the original dataset
- **task_id** contains task ID as in the original dataset
- **state** contains state annotation by authors, 1- exploration, 2- exploitation, 3- knownitem

## eval_state_analysis_cikm21.R
contains R code for state-aware evaluation (corr with user satisfaction, see Section 2.3 in paper). 

## state_prediction.ipynb
contains source code used for predicting (classifying) search state based on pre-computed features.
