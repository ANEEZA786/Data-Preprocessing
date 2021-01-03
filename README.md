# Data-Preprocessing Outlier Removal
Feature Engineering is important step of Machine learning project deployment which ultimately helps to improve the accuracy of model. In the given project removed outlier (the data which is out lie, in other words 
out of range data(error))by using different statistics techniques like percentile, Standard Deviation & Z-score are used to remove it.
In first file removes outlier using percentile of human height and secondly, contain the dataset of house prices_per_sqr_ft at different areas using 'Percentile' technique.
In second file removes outlier on both of the same files at first using'Standard Deviation' and then 'Z_score' technique.
Percentile technique used to tell a particular datapoint rank at which level.
Whereas, Standard deviation & Z-score are related to each other. Standard deviation tells a particular datapoint lies how far from the mean. Whereas, Z-score tells how far a datapoint
lie away from the mean.
I have provided the link of dataset of both files here as well:
https://drive.google.com/file/d/1BDo_PrdmSOVTB2iDSuy1yHAYSZtXkYK-/view?usp=sharing(height.csv)
https://drive.google.com/file/d/1mkFWRN8GLQvLvGOR1YO3O6JSCDLIilay/view?usp=sharing(bhp.csv)

# Handling Missing Values
Data can have missing values for a number of reasons such as observations that were not recorded, data corruption and many more.
Handling of that missing values is important because many Machine Learning algorithms do not support data with missing values.
In this repo, uploaded a file named "Handling Missing Values" in which two techniques were used to solve this issues.
Firstly, remove rows which containing the missing value from that dataset.
Secondly, impute missing values with mean values in the dataset.
As removing rows that containing missing values is not a good strategy. So prefer to use second method to save the information of dataset.

# Label Encoding (Conversion of Categorical data into Numerical data)
Machines are unable to understand the categorial data. So, it is important to convert that categorical data into numerical data.
Ordinal data is a categorical, statistical data type where the variables have natural, ordered categories and the distance b/w the categories is not known.
When the categorical Variables are ordinal, the most straightforward best approach is to replace the label by some ordinal numbers based on their rank.
