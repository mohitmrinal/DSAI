# DSAI
For the project in Data Science &amp; AI

Title: Investigating Bias Mitigation Algorithms in Predicting Student Dropout and Credit Card Approval

## We used the IBM AIF360:

Documentation: https://aif360.readthedocs.io/en/latest/modules/sklearn.html

Github Repository: https://github.com/Trusted-AI/AIF360

## Research questions:

- How do different bias metrics vary across the student dropout prediction and credit card approval datasets?
- How do different bias mitigation algorithms affect the bias metrics in both datasets? And which is the most suitable one?
- Which bias metrics show the most significant change after applying bias mitigation algorithm we selected?

## Our Datasets

1. Student Dropout Rate Prediction: https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success
2. Credit Card Approval Prediction: https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction

In these datasets, we define different use cases to assess fairness. The selected protected attributes for each dataset are:

- **Student Dropout Rate Prediction**:
  - Gender
  - Marital Status [Married or not]
  - Previous Qualification [Graduation]
  - Mother’s Qualification [Graduation]
  - Father’s Qualification [Graduation]
  

- **Credit Card Approval Prediction**:
  - Gender
  - Marital Status [Married or not]
  - Education [Higher or not]
 

The entire project code (with output) is available as 'notebook.ipynb' and 'notebook.html'

# Thanks
