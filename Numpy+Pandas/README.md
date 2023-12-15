# Numpy+Pandas README

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



## Pandas-Titanic-Flights-Penguins
1. **Titanic Dataset:**
   - Read and inspect using `.info()`, `.head()`.
  ![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/389b924c-dd75-4680-b5c7-5dc2dd4c7895)
   - Use seaborn's `.hist()` to display age frequency.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/bddb4d70-2e8a-4905-9816-65f248b4add8)
   - Utilize `pivot_table()` for in-depth analysis of males and females that survived, aggregate on count.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/f323fb62-67e5-4890-a8a0-e5badba7f0d0)
  
2. **Airlines Dataset:**
   - Read and analyze arrival delays; handle missing data with `.dropna()`.
   - Find the top 5 airlines with the highest arrival delay using `flights.groupby('AIRLINE').mean(numeric_only=1)['ARRIVAL_DELAY'].sort_values(ascending=False).head(5)`.
   ![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/f1080cba-0c17-40b0-9f2c-2aee9a815f2c)

   - Find the top 5 airlines with the lowest arrival delay using `flights.groupby('AIRLINE').mean(numeric_only=1)['ARRIVAL_DELAY'].sort_values().head(5)`.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/9ba313e8-af80-4b34-9068-b2489c4a45dc)


3. **Penguins Dataset:**
   - Explore 'penguins' dataset for visualization with seaborn's functions.
   - Create a displot to visualize 'flipper_length_mm' with hue 'island' and column 'species' using `sns.displot(data=penguins, x="flipper_length_mm", hue="island", col="species")`.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/586fc8ab-9357-4df0-a3bf-abf65612fc7c)
    - Generate a pairplot for the penguins dataset using `sns.pairplot(data=penguins)`
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/391413ce-cba1-426d-9196-13b25add7be3)











