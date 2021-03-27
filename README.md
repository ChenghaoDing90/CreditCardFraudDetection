# CreditCardFraudDetection
## Goals:
<ol>
<li>Understand the little distribution of the "little" data that was provided to us.</li>
<li>Create a 50/50 sub-dataframe ratio of "Fraud" and "Non-Fraud" transactions. (NearMiss Algorithm)</li>
<li>Determine the Classifiers we are going to use and decide which one has a higher accuracy.</li>
<li>Create a Neural Network and compare the accuracy to our best classifier.</li>
<li>Understand common mistaked made with imbalanced datasets.</li>
</ol>

Gather Sense of Our Data:
The first thing we must do is gather a basic sense of our data. Remember, except for the transaction and amount we dont know what the other columns are (due to privacy reasons). The only thing we know, is that those columns that are unknown have been scaled already.

Summary:
The transaction amount is relatively small. The mean of all the mounts made is approximately USD 88.
There are no "Null" values, so we don't have to work on ways to replace values.
Most of the transactions were Non-Fraud (99.83%) of the time, while Fraud transactions occurs (017%) of the time in the dataframe.
Feature Technicalities:
PCA Transformation: The description of the data says that all the features went through a PCA transformation (Dimensionality Reduction technique) (Except for time and amount).
Scaling: Keep in mind that in order to implement a PCA transformation features need to be previously scaled. (In this case, all the V features have been scaled or at least that is what we are assuming the people that develop the dataset did.)



