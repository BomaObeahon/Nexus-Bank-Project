# Nexus-Bank-Project
Tools used for this project are:
1.	Jupyter notebook – for experimenting with the project.
2.	Pandas – for loading data as a dataframe and cleaning the data.
3.	Numpy and Scipy – for performing some basic mathematical computations.
4.	Scikit-Learn – for building Customer Segmentation Model.
5.	Seaborn, Matplotlib and Plotly Express – for data visualization.
   
The dataset had 45,211 rows and 17 columns with zero duplicates and missing values.
Some columns were renamed for better understanding. 2 new columns were created namely age group from the age column and season column from the month column.

3 phases of Exploratory Data Analysis were performed which were:
1.	Univariate Analysis – this evaluates one feature/column.
2.	Bivariate Analysis- this evaluates or compares 2 features/columns.
3.	Multivariate Analysis- this evaluates more than 2 features/columns.

Supervised machine learning: is when a machine is trained using labeled data.

The algorithms used are:
1.	Random Forest Algorithm
2.	Decision Tree
3.	Logistic Regression
4.	KNeighbor
   
Evaluation metrics used:
1.	Accuracy Score
2.	Precision
3.	Recall
4.	Confusion Matrix
5.	F1 Score
6.	AUC ROC
   
Unsupervised machine learning: uses machine learning algorithms to analyze and cluster unlabeled datasets which discovers hidden patterns without human help.
The Algorithm used is the K Means algorithm. This works by simply splitting N number of observations into K numbers of clusters.
The elbow method is used to select the best cluster. It works simply by plotting the error from each cluster and looking for a spot that forms an elbow on the plot. As a result, the ideal cluster gotten was 5.
