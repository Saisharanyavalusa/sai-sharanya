DBSCAN is an algorithm of un-supervised machine learning algorithm 
it is a clustering algorithm which clusters the data according to the data points.
PARAMETER:
eps:
min_pts:

DATA CLEANING: Mall_customers.csv contains columns gender,age,annual_income,spending_range(100).As the data explains about how certain age group of customers spending thier annual_income .
Pandas used for data cleaning as there are no null values in the data ,used drop() to drop the unwanted data such as customer_id,gender.
EDA: compiled correlation of the data using seaborn while plotting with heatmap.
used eps=10.5 and min samples 5 as it is giving good results.
plotted clusters using scatter from seaborn
