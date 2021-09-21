# BPJS_Hackathon
Repositories of Python IPYNB Used At The BPJS Hackathon 2021

The Problem Chosen Are Fraud Classification

## Model Used
The Model Used is this Notebook is Random Forest

## Feature Engineering
Using Mean Encoding and Min Max Scaler for variables

## Training and Parameter Tuning
Using Stratified K-Fold to split the Training Data (since the data given are only the train and val data, so to utilize the train data to the fullest, we use Stratified K-Fold)
Using Gridsearch to search the parameter (Using Manual Search before to choose the best params and then fit it into the GridSearch)

## Evaluation
F1-Score as the main evaluation parameter.

## Result
My team scored on the top 12 in the final Leaderboard. 

## Conclusion
Actually there are still a lot of improvement that can be made to achieve higher F1-Score and better prediction. Also due to our data limitation, if we can expand the data scope, then we can achieve much better score. The tuning and the classification methods still can produce better result if we did not bound by time constraint at that time.
