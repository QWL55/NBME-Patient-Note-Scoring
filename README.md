# NBME-Patient-Note-Scoring

This repository is the implementation of our final project for CMSC 35100 Natural Language Processing at the University of Chicago. Using a collection of patient notes from Step 2 Clinical Skills examination data from National Board of Medical Examiners (NBME), we train medical concept extractors that achieve satisfactory performance on mapping clinical concept features to word sequences expressed in clinical patient notes. Our best model achieves 0.928 F1 score on the validation set and 0.797 on the test set.

My contribution to the implementation includes:

- Conducted the exploratory data analysis
- Re-wrote the version 1 script to make it easier to customize the hyperparameters setting for different models
- Trained all the models we presented in the poster
- Set up the notebooks and model files in Kaggle and submit all models to Kaggle
- Wrote the function that converts token-level prediction to string location
- Wrote functions to calculate metrics for all models at the pooled and sub-group level
- Conducted error analysis and annotation plotting

For the report, I contribute to:

- A part of the literature review
- Data Overview and Exploratory Data Analysis
- Methods (except the pre-processing subsection)
- Results
- Limitations
- All figures and tables