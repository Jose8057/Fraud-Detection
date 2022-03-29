# Fraud-Detection
In Banking or payment industry, fraud is an illegal usage of credit card details without the real cardholder’s knowledge. A stolen credit card/card number is usually the cause of a fraudulent charge. Once a cardholder sees a payment transaction he did not make on his credit card statement, he/she has the right to dispute the charge by contacting his/her bank. The bank or credit card company conducts an investigation and returns the money to the cardholder.

But what if we can detect the fradulent transaction activity in real time? By that way we can take the required action to stop the same.

We can use machine learning technique to detect the fraudulent transaction


Isolation Forest
Isolation Forests is similar to Random forests that are built based on decision trees.

There are no pre-defined labels here and hence it is an unsupervised algorithm.

It weas built based on the fact that anomalies or outliers are the data points that are “few and different”.

In an Isolation Forest, randomly sub-sampled data is processed in a tree structure based on randomly selected features.

The sub-samples that travel deeper into the tree are less likely to be anomalies as they required more cuts to isolate them.

The one which end up in shorter branches indicate anomalies as it was easier for the tree to separate them from other observations.
