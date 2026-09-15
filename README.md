# EDA on Haberman's Survival Dataset

## About :
  This project focuses on data cleaning, data preprocessing, data organization, and exploratory data analysis of the Haberman's Survival dataset. I used different statistical techniques and graphs to analyze the features, understand their distributions, and identify relationships and patterns in the data.
  
   This project is used to analyze whether a patient survived for at least 5 years after surgery (Survival_status) based on other factors, such as the patient's age, year of operation, and number of positive lymph nodes detected. In this project, these features are explored using data cleaning, preprocessing, statistical analysis, and EDA with different graphs and visualizations, without training a machine learning model.

## Dataset : Haberman's Survival data 
  It contains records of patients who underwent surgery for breast cancer at the University of Chicago's Billings Hospital, with the study covering 1958–1970. It has 306 observations and 3 input features, plus 1 target variable, with no missing values.
  
  This dataset contains four features/columns :
  Feature	                                 Meaning
  Age	                           Age of the patient at the time of operation
  Year	                         Year of operation, represented as year - 1900
  Positive_lymph_nodes	         Number of positive axillary lymph nodes detected
  Survival_status	               Whether the patient survived at least 5 years after surgery

## Tools used : 
  - python
  - pandas
  - matplotlib
  - seaborn

## Key findings : 
  - Most patients survived 5 years or longer.
  - The dataset contains more surviving patients than non-surviving patients.
  - Age shows variation among patients.
  - Most patients had fewer positive lymph nodes.
  - Higher positive lymph nodes are generally associated with lower survival.
  - The year of operation has less noticeable impact on survival.
  - The dataset contains no missing values.
  - Survival_status is the target/outcome feature.
