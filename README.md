# Machine-Learning-Study-Notes
Interactive Colab notes showing my study journey through the Datacamp Machine Learning Scientist track.
# Contents
## Course 1: SciKit-Learn Supervisized Learning
#### chap 1: classification
- *models*: k nearest neighbors (KNN)
- *metrics*: model.score() (accuracy rate)
- *tools*: using bulit-in datasets, numerical and visual EDA, hyperparameter tuning 
- *visualization*: visual EDA, accuracy as a function of the hyperparameter k in KNN
#### chap 2: regression
- *models*: Linear Regression, Ridge Regression, Lasso Regression
- *metrics*: linear_model.score() ($R^2$), cross_val_score(), mean_squared_error()
- *tools* : cross validation (cv), l1 (lasso) regularization, l2 (ridge) regularization, l1 regularization as a tool to select important features
- *visualization*: coefficients of features 
#### chap 3: fine tuning your model
- *models*: Logistic Regression, Elastic Net, Decision Tree Classifier
- *metrics*: confusion_matrix, classfication_report, roc_curve, roc_auc_score
- *tools*: grid search vs randomized search for hyperparameter tuning
- *visualization*: ROC space
#### chap 4: preprocessing
- *models*: SVC 
- *tools*: imputer and scaler for preprocessing; pipeline 
## Course 2: Unsupervised Learning in Python
#### chap 1-2: visualize & find dataset clustering 
- *visualization*: dendrogram, t-SNE, inertia plot
- *model*: KMeans
- *metrics*: inertia of kmeans, single vs complete linkage between clusters in hierarchy clustering
- *tools*: fcluster to extract cluster labels from some intermediate stage of hierarchy clustering
