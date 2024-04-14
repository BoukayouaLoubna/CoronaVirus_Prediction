# CoronaVirus_Prediction

## Exploratory Data Analysis

### Objective:
The objective of the exploratory data analysis (EDA) is to understand the dataset and develop an initial modeling strategy.

### Basic Checklist

#### Shape Analysis:
- **Target variable:** SARS-Cov-2 exam result
- **Rows and columns:** 5644 rows, 111 columns
- **Types of variables:** 
  - Qualitative: 70
  - Quantitative: 41

#### Missing Values Analysis:
- Many NaNs present (more than 90% in half of the variables)
- Data divided into 2 groups:
  - 76% missing values in Viral test group
  - 89% missing values in Blood levels group

#### Substance Analysis:
- **Target Visualization:**
  - 10% positive cases (558 out of 5000)
  
- **Variable Significance:**
  - Standardized continuous variables, skewed, blood test
  - Age quantile: difficult to interpret due to lack of context
  - Qualitative variable: binary (0, 1), viral, Rhinovirus appears high
  
- **Variable / Target Relationship:**
  - Relationship between certain blood levels (Monocytes, Platelets, Leukocytes) and COVID-19 observed
  
  - Observation regarding age and likelihood of COVID-19 infection
  
  - Rare occurrence of double diseases; hypothesis to be tested
  
### More Detailed Analysis

#### Variable / Variable Relationship:
- Correlation analysis between blood data variables
  
- Weak correlation observed between age and blood levels
  
- Influenza rapid test results are poor, may need to be dropped
  
#### Disease / Blood Data Relationship:
- Blood levels vary between sick and COVID-19 patients
  
#### Hospitalization / Illness Relationship:
- Potential for predicting patient department based on hospitalization
  
#### Null Hypotheses (H0):
- Individuals with COVID-19 have significantly different levels of Leukocytes, Monocytes, and Platelets
