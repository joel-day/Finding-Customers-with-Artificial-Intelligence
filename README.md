# Finding-Customers-with-Artificial-Intelligence

# Problem
The business desires the ability to predict if someone will make a deposit. Given a new list, our model will predict whether each individual will make a deposit. Recall is used to measure performance., the decision to prioritize minimizing false positives or false negatives came down to business resources. This particular  business has the resources to take its time and reach out to a large portion of the full client list. Meaning this model wants to ensure it finds all the people who will make a deposit. That means it will minimize the amount of times that it precited a customer would no when it was yes. (lost profit). This is done at the expense of more false positives (wasted resources). In this case a false positive is predicting someone will make a deposit and they don't. I use recall to minimize false negatives.

# Best Model
Logistic Regression is the best model with a recall of 98%.
