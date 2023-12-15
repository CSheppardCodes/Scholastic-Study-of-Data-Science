# readme for numpy and pandas

## Basic-Numpy
 - array operations, matrix handling, and basic calculations in NumPy.
 - array creation, slicing, matrix multiplication, and common errors.

## DataFrame
1. **Data Handling:**
   - pd.DataFrame(data): Creates a Pandas DataFrame from a dictionary. df.describe(): Generates descriptive statistics for numeric columns.
 2. **Indexing and Slicing:**
    - df.loc[['a','b'],'x':'y']: Retrieves specific rows and columns using labels. df.iloc[0,:]: Selects a single row as a Pandas Series.
 4. **Applying Functions:**
    - my_data.apply(lambda x: 2*x): Applies a lambda function to double each element in a column.
 6. **Filtering and Sorting:**
    - df[(condition)]: Filters rows based on specified conditions. df.sort_values(by=['salary', 'service'], ascending=False): Sorts DataFrame by specified columns in descending order.






## basicDF
1. **Data Preparation:**
   - Use NumPy & Pandas to represent a dataset with features 'x' and target variable 'y'.
 2. **Model Training:**
    - Utilized Decision Tree Regressor from scikit-learn to train a regression model on the dataset.
 4. **Visualization:**
    ![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/ef7805aa-5748-4605-af8a-65e72157d1e9)
 6. **Statistical Summary:**
    - Generated descriptive statistics using df.describe() and df['y'].describe() to understand the dataset and target variable 'y'.



## Pandas
1. **DataFrame Manipulation:**
   - Constructed and manipulated DataFrames using Pandas and NumPy (pd.DataFrame, pd.Series, pd.read_csv).
 2. **Descriptive Statistics:**
    - Employed Pandas functions (describe(), info(), mean(), sort_values()) for comprehensive data analysis.
 4. **Data Exploration:**
    - Utilized Pandas' isin(), mean(), and isna().sum() for conditional filtering and checking null values.
 6. **Advanced Sorting:**
    - Applied Pandas' sort_values() with multiple columns for data organization.















