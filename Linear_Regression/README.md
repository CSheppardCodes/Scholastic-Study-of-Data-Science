# Linear Regression readme

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

