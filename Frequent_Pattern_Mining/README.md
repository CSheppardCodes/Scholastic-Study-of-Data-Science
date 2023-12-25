# Frequent Patter Mining README

## Part 1 Introduction:
- Association rule mining using the Apriori algorithm.
- Objective: Reveal meaningful patterns and associations in a transaction dataset.

## Dataset:
- List of transactions, each a unique combination of items.
- `Milk` - `Onion` - `Nutmeg` - `Kidney Beans` - `Eggs` - `Yogurt` - `Dill` - `Apple` - `Unicorn` - `Corn` - `Ice cream`

## Approach:
- Apriori algorithm employed for discovering frequent itemsets and association rules.
- Algorithm establishes connections between frequently co-occurring items.

## Data Preparation:
- Transaction list transformed using mlxtend's TransactionEncoder.
- Binary matrix created, denoting presence or absence of items in transactions.

## Insights from Apriori Algorithm:
- Minimum support threshold: 60%
- Revealed frequent itemsets, combinations, and association rules.

![image](https://github.com/CSheppardCodes/Study-of-Data-Science/assets/78242653/da36c916-b5b2-4b61-abac-bf24a99e8d48)


# Part 2. Analyzing Online Retail Data Using Apriori Algorithm

## Dataset Overview:
- **Source:** UCI Machine Learning Repository
- **Dataset:** [Online Retail](https://archive.ics.uci.edu/ml/datasets/online+retail)
- **Description:** The dataset captures online retail transactions, including details such as invoice number, stock code, description, quantity, invoice date, unit price, customer ID, and country.
- **Processing:** Cleaned the dataset by removing null or missing invoice values and converting them to string format.

## Data Transformation:
- **Objective:** Convert data into the required format for the Apriori algorithm.
- **Approach:** Created a transactional dataset with transaction IDs along rows and one column for each item.

## Apriori Algorithm and Association Rules:
- **Library Used:** MLxtend for Apriori algorithm.
- **Processing:** Applied the Apriori algorithm to extract frequent itemsets with a minimum support of 7%.

## Results and Insights:
- **Frequent Itemsets:** Identified various itemsets with their support in the dataset.
- **Association Rules:** Extracted rules with metrics such as confidence, lift, and support, providing insights into item relationships.

### Example Association Rule:
- **Antecedents:** (ALARM CLOCK BAKELIKE PINK)
- **Consequents:** (ALARM CLOCK BAKELIKE GREEN)
- **Support:** 0.073980
- **Confidence:** 0.725000
- **Lift:** 7.478947

## Conclusion:
- **Objective:** Uncovered patterns and associations in online retail transactions.
- **Significance:** This analysis can aid in understanding customer behaviors, optimizing inventory, and driving targeted marketing strategies.
