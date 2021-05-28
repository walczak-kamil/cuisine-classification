# cuisine-classification

## Dataset used is called whats_cooking dataset from kaggle competition<br>
## Main goal was to classify cuisine type judging by list of ingredients in recipe
<br>
Firstly text was preprocessed by regex templates, stop words (with added custom ones)<br>
Then text was tokenized by CountVectorizer<br>
LogisticRegression and RandoForestClassifier were main classifiers in this task<br>
Classification results were checked using confusion matrix and accuracy score<br>
<br>
In unsupervised part I used PCA, k-means clustering with silhouette metric
