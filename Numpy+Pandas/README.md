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




