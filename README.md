<h1>Predicting Prices of Used Toyota Corolla Cars</h1>


This project focuses on predicting the prices of used Toyota Corolla cars using various machine learning algorithms. The analysis includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and visualization of the results. The primary goal is to determine which machine learning model performs best in predicting car prices.

<h3>Key Insights and Findings</h3>

1.	Data Preprocessing:

    •	Missing Values: Handled missing values in the dataset by removing rows with missing target values and imputing or removing rows with missing feature values.
  	
  	•	Categorical Features: Encoded categorical features using one-hot encoding to prepare the data for model training.
  	
  	
2.	Exploratory Data Analysis (EDA):
   
    •	Distribution of Prices: Visualized the distribution of car prices to understand the target variable better.

    •	Correlation Analysis: Identified key features that are strongly correlated with car prices, such as mileage, year of manufacture, and engine size.

3.  Feature Engineering:
   
    •	New Features: Created new features such as age of the car to improve model performance.

    •	Feature Selection: Selected the most relevant features based on correlation analysis and domain knowledge.

4.	Model Training and Evaluation:

    •	Linear Regression: Trained a linear regression model and evaluated its performance using R-squared and mean squared error (MSE).
  	
    •	K-Nearest Neighbors (KNN): Trained KNN models with different values of k (5 and 10) and compared their performance.
  	
    •	Random Forest: Trained a Random Forest model and evaluated its performance.
  	
5.	Performance Comparison:
   
    •	R-squared Values: Compared the R-squared values of different models to determine their predictive power.
  	
    •	Visualization: Visualized the performance of each model using bar plots to provide a clear comparison.
  	

<H3>Results</H3>

    •	Linear Regression: Achieved the highest R-squared value of 0.8495, indicating the best performance among the tested models.
    •	KNN (k=5): Achieved an R-squared value of 0.8265.
    •	KNN (k=10): Achieved an R-squared value of 0.8309.
    •	Random Forest: Achieved an R-squared value of 0.8276.

<H3>Conclusion</H3>
The linear regression model outperformed the other models in predicting the prices of used Toyota Corolla cars. This project demonstrates the importance of feature engineering and model selection in building effective predictive models. The findings highlight that simpler models like linear regression can sometimes provide better performance than more complex models.

