# Tech Compensation Analysis

This project analyzes 9,355 tech job records to identify key salary drivers and build a salary prediction model.

## Project Goals
- Perform structured exploratory data analysis  
- Identify factors affecting compensation  
- Apply regression models to predict salary  
- Evaluate model performance using standard metrics  

## Project Workflow
- Data loading and validation  
- Outlier treatment (1st–99th percentile capping)  
- Log transformation of salary  
- Experience level analysis  
- Company size analysis  
- Work setting analysis  
- Job category analysis  
- Location analysis  
- Feature engineering (one-hot encoding + grouped locations)
- Baseline linear regression model  
- Model evaluation (R², MAE, RMSE)
- Feature importance analysis using linear regression coefficients

## Tools Used
- Python  
- pandas  
- NumPy  
- matplotlib
- scikit-learn

## Final Results
- Built a baseline linear regression model to predict salary  
- Achieved R² = 0.436, explaining 43.6% of salary variation  
- Key drivers identified: experience level, job category, and location

## Key Findings
- Salary increases significantly with experience level, with the largest jump from Mid-level to Senior roles  
- ML/AI roles have a median salary of $176,000, the highest across all job categories 
- Location plays a major role, with US-based roles showing higher salaries compared to other countries  
