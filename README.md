CSC542 Final Project: Evaluating Comparable-Sales and Machine Learning Approaches for House Price Prediction

1. Project Overview: 
   This project compares traditional comparable-sales logic (KNN) with Random Forest machine learning models for residential property valuation using the Ames Housing dataset.

2. Research Questions: 
  Can machine learning models outperform the traditional comparable-sales approach in predicting house prices?
  How do model performances vary across Low-End, Mid-Range, and Luxury tiers?
  Which housing characteristics most strongly influence property value?

3. Repository Structure: 
  README.md
  data/.Rhistory
  data/data_description.txt
  data/sample_submission.csv
  data/sample_submission.csv.gz
  data/test.csv
  data/test.csv.gz
  data/train.csv
  data/train.csv.gz
  docs/CSC542 Final Report.pdf
  docs/CSC542 Slide.pdf
  src/CSC542 Project.R

4. Dataset: 
   Ames Housing Dataset (De Cock, 2011)
   
5. Methods: 
    Data cleaning
    Feature engineering
    Log transformation
    Train/test split (80/20)
    KNN with 10-fold cross-validation
    Random Forest (500 trees)
   
6. Key Results: 
    Random Forest outperformed KNN overall.
    Mid-Range homes had the highest valuation accuracy.
    Luxury homes showed greater prediction uncertainty.
    
7. How to Run: 
    Open `src/CSC542 Project.R` in RStudio and run the script.
    
8. Author: 
    Ximena Chen, Jenny Nguyen, Kai Binatti
