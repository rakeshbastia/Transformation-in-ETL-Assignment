# Transformation in ETL – Assignment Answers

## Question 1: Define Data Transformation in ETL and explain why it is important.
### Answer:
Data Transformation in ETL means changing the data from its original format into a format that
can be easily used in the target system. It can include cleaning the data, changing its format,
removing unwanted data, or making values consistent.
It is important because data usually comes from different sources and may not be in the same
format. Transformation makes the data clean, accurate, and consistent, which helps in better
analysis and decision-making.

## Question 2: List any four common activities involved in Data Cleaning.
### Answer:
Some common activities involved in data cleaning are:
1. Handling missing values – Filling missing data or removing records when necessary.
2. Removing duplicate records – Finding and deleting repeated data.
3. Correcting inconsistent data – Making values follow the same format.
4. Correcting incorrect data – Finding invalid or wrong values and fixing them.
These activities help make the dataset more reliable and useful.

## Question 3: What is the difference between Normalization and Standardization?
### Answer:
Normalization and Standardization are both techniques used to change the scale of data, but they
work differently.
Normalization usually changes the values into a fixed range, mostly between 0 and 1.
Standardization changes the data so that its mean becomes 0 and standard deviation becomes 1.
In simple words, normalization focuses on bringing values into a fixed range, while
standardization focuses on adjusting the data around its mean.

## Question 4: A dataset has missing values in the “Age” column. Suggest two techniques to handle this and explain when they should be used.
### Answer:
There are different ways to handle missing values in the Age column. Two common methods
are:
1. Replace the missing values:
We can replace the missing age values with the mean or median age. Median is usually useful
when there are some very high or very low ages in the data.
2. Remove the records:
We can remove the rows where the Age value is missing. This method is suitable when only a
small number of records have missing values and removing them will not affect the dataset
much.

## Question 5: Convert the following inconsistent “Gender” entries into a standardized format (“Male”, “Female”).
Given entries: ["M", "male", "F", "Female", "MALE", "f"]
### Answer:
After standardizing the entries, they will become:
["Male", "Male", "Female", "Female", "Male", "Female"]
Here, M, male, and MALE are changed to Male, while F and f are changed to Female.

## Question 6: What is One-Hot Encoding? Give an example with the categories: “Red, Blue,Green”.
### Answer:
One-Hot Encoding is a method of converting categorical data into numbers so that it can be
easily used by a machine learning model.
For example, if we have three colors - Red, Blue, and Green, they can be represented like this:
Color Red Blue Green
Red 1 0 0
Blue 0 1 0
Green 0 0 1
Here, 1 means that the category is present and 0 means that it is not present.

## Question 7: Explain the difference between Data Integration and Data Mapping in ETL.
### Answer:
Data Integration means bringing data from different sources together into one system. For
example, data from different databases or files can be combined into a single system.
Data Mapping is about deciding how the fields from the source will match the fields in the target
system. For example, a source field called Customer_Name may be mapped to a target field
called Name.
So, in simple terms, Data Integration combines data, while Data Mapping shows where each
piece of data should go.

## Question 8: Explain why Z-score Standardization is preferred over Min-Max Scaling when
outliers exist.
### Answer:
When a dataset has outliers, Min-Max Scaling can be affected a lot because it uses the minimum
and maximum values of the dataset. A very large or very small value can change the scale of the
other values.
Z-score Standardization uses the mean and standard deviation to transform the data. Because of
this, it is often preferred when outliers are present.
In simple words, Min-Max Scaling can be strongly affected by extreme values, while Z-score
Standardization is generally more suitable when the dataset contains outliers.
