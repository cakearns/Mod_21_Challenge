ReadMe
# Unit 21 Homework: Charity Funding Predictor
Imported depenencies and csv
Dropped Names and EIN
Used application_df.nunique()to determine unique values in each column
Cut off value - used: appcount = application_df["APPLICATION_TYPE"].value_counts()with 500 as the cut off
Dropped EIN and NAME
Created a for loop to loop through appcounts, apptype, classification with `pd.get_dummies`
Convert categorical data to numeric with `pd.get_dummies`

1st Iteration: Accuracy: 0.7237317562103271
2nd Iteration: dropped only EIN and got .9654 accuracy


