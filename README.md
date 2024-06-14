# Credit Risk Modeling for Consumer Loans

## Project Overview
This project involves a comprehensive analysis and modeling of credit risk using the Lending Club dataset, which includes complete loan data from 2007 to 2015. The aim is to predict the probability of default (PD),loss given default (LGD), and exposure at default (EAD) on consumer loans, such as credit cards, and assess potential expected loss (EL) using various statistical and machine learning techniques.

## Data
The dataset encompasses a wide range of features including employment length, education, number of finance inquiries, borrower's address details (zip codes and state), and collections among other variables. Data source: https://www.kaggle.com/datasets/adarshsng/lending-club-loan-data-csv

## Methodologies and Techniques
### 1. Data Preparation
Preprocessing Continuous and Discrete Variables, incorporating weight of evidence (WoE) and information value (IV) :
- Fine Classing: Applied fine classing to categorize continuous variables into meaningful groups.
- Coarse Classing: Coarse classing was then used to merge these categories based on similar characteristics or behaviors.
- Creating Dummies: For categorical variables, dummy variables were created to convert them into a format suitable for modeling.

### 2. Model Building
- Logistic Regression for PD: Utilized dummy variables and checked model significance using p-values.
- Logistic Regression and Linear Regression for LGD and EAD: 
- Estimate recovery rates and credit exposure
- Use a two-step model instead of beta regression to better efficiency

### 3. Model Validation and Performance Evaluation
- Splitting Data: Divided the data into training and validation sets to ensure model robustness.
- Out-of-Sample Validation: Performed to test the model on unseen data (year 2015).
- Accuracy and AUC: Evaluated model performance using accuracy metrics and Area Under Curve.
- Gini and Kolmogorov-Smirnov: Additional metrics to assess the discriminatory power of the model.

### 4. Application of Model
- Scorecard Creation: Developed a scorecard to translate model outputs into a user-friendly format.
- Probability of Default Calculation: Computed for individual customers to inform lending decisions.
- Setting Cut-Offs: Established thresholds for decision-making based on the scorecard.

### 5. Monitoring
Population Stability Index (PSI): to check the stability of the model over time and assess the need for recalibration.

## Tools and Libraries Used
- Pandas and NumPy: For data manipulation and numerical calculations.
- Matplotlib and Seaborn: To visualize WoE for fine classing and coarse classing.
- Scikit-Learn: For logistic and linear regression modeling and model evaluation.

## Conclusion
- Deepened Understanding of Credit Risk Concepts: I've thoroughly grasped the critical aspects of Expected Loss (EL) and its crucial components: Probability of Default (PD), Loss Given Default (LGD), and Exposure at Default (EAD).
- Engagement with Regulatory Frameworks: My exploration of capital adequacy and the Basel II accord has enriched my understanding of various approaches, including the Standardized Approach (SA), Foundation Internal Ratings-Based Approach (F-IRB), and Advanced Internal Ratings-Based Approach (A-IRB).
- Familiarization with Core Credit Risk Modeling Methods: I have deeply familiarized myself with fundamental methods in credit risk modeling, specifically fine classing and coarse classing. These techniques are critical for detailed risk analysis, enabling the effective segmentation and interpretation of complex data sets. 
- Practical Application of Statistical Techniques: This project allowed me to apply statistical and machine learning methods effectively, ensuring rigorous data preparation, robust model evaluation, and continuous model monitoring.
