# ML_PROJECT
Binary Classification

You will be predicting the probability [0, 1] of a binary target column.
Dataset contains only categorical features, and includes:
1. binary features (bin_*),
2. low - and high-cardinality nominal features (nom_*),
3. low - and high-cardinality ordinal features (ord_*), and
4. (Potentially) cyclical features (day and month).
The string ordinal features ord_{3-5} are lexically ordered according to string.ascii_letters.
The data has missing values and feature interactions.
Files:
train.csv - the training set
test.csv - the test set; you must make predictions against this data
sample_submission.csv - a sample submission file in the correct format
