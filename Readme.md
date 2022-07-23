## Drug Prediction

### Overview:
- Use/implement a feature selection/reduction technique.
- Experiment with various classification models.
- Dealing with imbalanced data.
- Use F1 Scoring Metric

### Detailed Description:
Drugs are typically small organic molecules that achieve their desired activity by binding to a target site on a receptor. The first step in the discovery of a new drug is usually to
identify and isolate the receptor to which it should bind, followed by testing many small molecules for their ability to bind to the target site. This leaves researchers with the task
of determining what separates the active (binding) compounds from the inactive (non- binding) ones. Such a determination can then be used in the design of new compounds
that not only bind, but also have all the other properties required for a drug (solubility, oral absorption, lack of side effects, appropriate duration of action, toxicity, etc.).
The goal of this competition is to allow you to develop predictive models that can determine given a particular compound whether it is active (1) or not (0). As such, the
goal would be develop the best binary classification model. A molecule can be represented by several thousands of binary features which represent their topological shapes and other characteristics important for binding. Since the dataset is imbalanced the scoring function will be the F1-score instead of Accuracy.

### Data Description:
- The training dataset consists of 800 records and the test dataset consists of 350 records
- We provide you with the training class labels and the test labels are held out. The attributes are binary type and as such are presented in a sparse matrix format within train.dat and test dat
Train data: Training set (a sparse binary matrix, patterns in lines, features in columns: the number of the non-zero features are provided with class label 1 or 0 in the first column.
Test data: Testing set (a sparse binary matrix, patterns in lines, features in columns: the number of non-zero features are provided).
Format example: A sample submission with 350 entries randomly chosen to be 0 or 1.
