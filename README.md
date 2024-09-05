**Fine-Tuning BERT for AI-Generated Text Detection**

This repository contains the code and resources for detecting AI-generated text using a fine-tuned BERT model. The project involves three main stages:

**Exploratory Data Analysis (EDA):** Refer to the Jupyter notebook "Scripts/EDA_bigbrain_ivypandaessays_NLP_git_v2.ipynb" for a basic EDA on datasets containing both human-written and AI-written texts to uncover patterns and distributions
within the data.

**Data Cleaning:** Data cleaning and preprocessing are essential to ensure high-quality input data. The Jupyter notebook "Scripts/clean_data_AIgen_hmnwrttn_text.ipynb" is dedicated to this task, which includes removing unnecessary columns, handling missing values, and preparing the text for analysis.

**Model Fine-Tuning:** After cleaning the data and understanding its structure, we proceed to fine-tune a BERT model specifically for the task of detecting AI-generated text in the notebook "Scripts/Fine_tune_hfc_detect_AIgen_text.ipynb". This work is currently in progress.

The ultimate goal is to develop a robust model that can accurately differentiate between human-written and AI-generated content.
