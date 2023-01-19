# Pandas-BootCamp
A comprehensive set of materials and tutorials for learning Python's Pandas package.
Pandas is a Python library that is widely used for data manipulation and analysis. It provides powerful data structures and data analysis tools that make it easy to work with large and complex data sets. The two primary data structures in pandas are the Series and the DataFrame. A Series is a one-dimensional array-like object that can hold any data type, while a DataFrame is a two-dimensional table-like object that can hold multiple Series.

Pandas provides a number of data manipulation and cleaning functions, such as merging, grouping, and pivoting, as well as advanced data analysis and modeling capabilities through its integration with other libraries such as NumPy and Matplotlib. Additionally, Pandas can work with data in a variety of formats, including CSV, Excel, and SQL databases, making it a versatile tool for working with data in a variety of contexts.

# Here is a quick cheat sheet of some common Pandas operations:
Creating DataFrames:
pd.DataFrame(data, columns) - creates a DataFrame from data (e.g. list of lists or dict) and specifies column names
pd.read_csv(file) - creates a DataFrame from a CSV file

#Viewing Data:
df.head() - displays the first 5 rows of the DataFrame
df.tail() - displays the last 5 rows of the DataFrame
df.info() - displays information about the DataFrame, including column names and data types
df.describe() - displays summary statistics for numerical columns

#Selecting Data:
df[col] - returns the column with the given name as a Series
df[[col1, col2]] - returns a new DataFrame with the specified columns
df.loc[row] - returns the row at the given index
df.iloc[row] - returns the row at the given position

#Filtering Data:
df[condition] - returns a new DataFrame with rows that meet the given condition
df[condition].any() - returns a boolean indicating whether any row in the DataFrame meets the given condition

#Grouping and Aggregating:
df.groupby(col) - groups the DataFrame by the given column
df.groupby(col).mean() - calculates the mean of each group
df.groupby(col).sum() - calculates the sum of each group
df.groupby(col).count() - calculates the count of each group
#Please note that this is not an exhaustive list and you should consult the Pandas documentation for more information.
