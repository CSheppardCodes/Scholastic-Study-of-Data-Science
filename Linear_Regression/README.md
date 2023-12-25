# Linear Regression readme

# Part 1: Abalone Age Prediction

## Dataset
- UCI Machine Learning Repository [Abalone Dataset](https://raw.githubusercontent.com/CSheppardCodes/MLDatasetsUCI/main/abalone/abalone.data)
- Attributes include Length, Diameter, Height, Whole weight, Shucked weight, Viscera weight, Shell weight, and Sex.
- Target variable: Rings (interpreted as abalone age).
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/342d8963-2932-460e-bac2-d111aa755935)
## Data Preprocessing
- One-hot encoding for categorical variable 'Sex'.
  
## Exploratory Data Analysis (EDA)
- Correlation analysis identifies features correlated with 'Rings'.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/207b468e-e8af-4412-9da6-6d6241efaea4)

## Algorithm
- Stochastic Gradient Descent Regressor (SGD) for age prediction.

## Model Training and Evaluation
- Standardization of features.
- Train-test split: 80-20.
- SGD Regressor performance:
  - Training Set: RMSE = 2.18, R2 = 0.54
  - Testing Set: RMSE = 2.33, R2 = 0.49.

## Ordinary Least Squares (OLS) Regression
- In-depth analysis using Statsmodels OLS:
  - R-squared: 0.548.
  - Significant feature contributions: Whole weight, Shucked weight, Sex_F, Sex_I, Sex_M.
  - Multicollinearity issues indicated.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/fb70aabb-d3ec-4499-9200-ed8159aae835)




# Part 2: StatsModelsAPI
## Building a Regression Model to Analyze the California Housing Dataset 
 
## Dataset Overview:
- **Source:** California Housing dataset
    `MedInc | HouseAge | AveRooms | AveBedrms | Population | AveOccup | Latitude | Longitude`

  - **Target:**
    - `MedHouseVal`: Median house value in California districts (in hundreds of thousands of dollars)
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/ba6a37ba-b5ab-4dad-b167-310b8b48f28d)

## Data Preprocessing:
- **Data Scaling:** Standardized features using StandardScaler to bring them within a comparable range.

## Exploratory Data Analysis:
- **Visualizations:** Employed Seaborn for visualizing the distribution of the target variable (MedHouseVal) and correlation matrix among features.
- **Correlation Analysis:** Examined correlations, identifying low correlations like HouseAge (0.11) and AveRooms (0.15).
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/c7bef58a-80f4-45ed-9692-e1d4a79a564c)

## SKLearn LinearRegression Model:
- **Libraries Used:** Pandas, Scikit-Learn, Statsmodels
- **Evaluation Metrics:** Used Root Mean Squared Error (RMSE) and R2 Score for model evaluation.

## Model Evaluation:
- **Training Set:**
  - RMSE: 0.732
  - R2 Score: 0.594
- **Testing Set:**
  - RMSE: 0.738
  - R2 Score: 0.606

## In-Depth Diagnostics using StatsModels:
- Utilized Statsmodels for detailed diagnostics, including coefficients, t-values, and confidence intervals.
- Identified statistically significant features: MedInc, AveRooms, HouseAge, Latitude, Longitude.
- Noted low correlation doesn't imply less statistical significance.
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/36697695-cec1-4b05-a492-920917c89267)


# Part 3: Online News Popularity Prediction

## Dataset
- **Source:** UCI Machine Learning Repository
- **Features:** Online news attributes
- **Target:** Number of shares

## Algorithm
- **Model:** SKLearn Stochastic Gradient Descent Regressor (SGD)
  - **Objective:** Predict online news popularity
  - **Libraries:** Pandas, Matplotlib, Seaborn, Scikit-learn, Statsmodels

## Data Preprocessing
- Load dataset, drop non-predictive columns, check for missing values, analyze data distribution
- Standardize features with Scikit-learn's StandardScaler

## Exploratory Data Analysis
- Correlation analysis to identify key features

## Model Training and Evaluation
- Train SGD Regressor with varied configurations
- Evaluate using RMSE and R-squared on training/testing datasets

## Results and Insights
- OLS regression for in-depth analysis
![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/43cbb301-ba8b-4888-9cd8-59e8d7393551)

