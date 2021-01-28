# Loan_approval_system
Use case is to automate the loan eligibility process (real time) based on customer detail obtained during loan application. This will lead to improved service and customer satisfaction.

## Classification
Classification -> Logistic Regression
### Advantages
- Classifies linearly separable data well
- Fast training speed and prediction speeds
- Does well on small datasets
- Decently interpretable results, easy to explain
- Easy to update the model when new data comes in
- Can avoid overfitting when regularized
- Can do both 2 class and multiclass classification
- No parameter tuning required (except when regularized, we need to tune the regularization parameter)
- Doesn't need feature scaling (except when regularized)
- If dataset has redundant features, linear regression can be unstable
### Disadvantages
- Doesn't work well for non-linearly separable data
- Low(er) prediction accuracy
- Can overfit (see regularized models below)
- Doesn't separate signal from noise well – cull irrelevant features before use
- Doesn't learn feature interactions in the dataset

Classification -> Support Vector Machine based
### Advantages
- High prediction accuracy
- Doesn't overfit, even on high-dimensional datasets, so its great for when you have lots of features
- Works well for small datasets (<100k training set)
- Work well for text classification problems
### Disadvantages
- Not easy to update the model when new data comes in
- Is very memory intensive
- Doesn't work well on large datasets
- Requires to choose the right kernel in order to work
- The linear kernel models linear data and works fast
- The non-linear kernels can model non-linear boundaries and can be slow
Use Boosting instead!

Classification - Naive Bayes (Probability based)
### Advantages
- Performs really well on text classification problems
- Fast training speed and prediction speeds
- Does well on small datasets
- Separates signal from noise well
- Performs well in practice
- Simple, easy to implement
- Works well for small datasets (<100k training set)
- The naive assumption about the independence of features and their potential distribution lets it avoid overfitting
- Also if this condition of independence holds, Naive Bayes can work on smaller datasets and can have faster training speed
- Decently interpretable results, easy to explain
- Scales well with the size of the dataset
### Disadvantages
- Low(er) prediction accuracy

Classification -> K Nearest Neighbors (distance based)

