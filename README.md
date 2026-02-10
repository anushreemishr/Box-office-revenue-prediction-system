# Box-office-revenue-prediction-system

# Objective
The objective of this project is to design and implement a Box Office Revenue Prediction System using Linear Regression techniques. The system aims to analyze the impact of various numerical movie attributes such as year, runtime, rating, votes, and metascore on box office revenue and predict revenue effectivel

# Dataset Description
The dataset contains the following numerical attributes:

- Rank  
- Year  
- Runtime (Minutes)  
- Rating  
- Votes  
- Revenue (Millions)  
- Metascore  

Missing values in important columns were handled appropriately, and irrelevant attributes were removed to prepare the dataset for modeling.

# Methodology
The project was implemented using the following step-by-step methodology:

1. **Data Loading**
   The dataset was loaded using Python libraries and basic information was analyzed.

2. **Data Cleaning and Preprocessing**  
   - Removed the Rank column as it does not contribute to prediction  
   - Handled missing values in Revenue and Metascore  
   - Verified the dataset for null values  

3. **Exploratory Data Analysis (EDA)**  
   - Analyzed statistical summaries  
   - Visualized relationships between features and revenue  
   - Used correlation analysis to understand feature dependencies  

4. **Model Implementation**  
   - Simple Linear Regression  
   - Multiple Linear Regression  
   - Polynomial Regression  
   - Ridge and Lasso Regression  

5. **Model Evaluation**  
   Models were evaluated using:
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  
   - R² Score  

6. **Model Diagnostics**  
   Residual plots were used to validate regression assumptions.

# Observations
- Movie revenue shows a positive correlation with votes and ratings.  
- Multiple Linear Regression performed better than Simple Linear Regression.  
- Polynomial Regression captured non-linear relationships more effectively.  
- Ridge regression helped reduce overfitting, while Lasso regression assisted in feature selection.  

# Team Contribution

# Member 1 (Anushree Mishra, CSJMA23001390278)
- Dataset loading and preprocessing  
- Exploratory Data Analysis and visualization
- GitHub documentation 

# Member 2 (Archana Yadav, CSJMA23001390279)
- Simple Linear Regression  
- Multiple Linear Regression  

# Member 3 (Padma Narayan Mishra, CSJMA23001390189)
- Polynomial Regression  
- Ridge and Lasso Regression  

# Member 4 (Vineet Kumar Singh, CSJMA23001390311)
- Model evaluation (MSE, RMSE, R²)  
- Residual analysis

# Tools and Technologies
- Python  
- Jupyter Notebook 
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

# Conclusion
The Box Office Revenue Prediction System successfully demonstrates how regression techniques can be applied to real-world datasets. The project provided hands-on experience in data preprocessing, model building, evaluation, and interpretation of results.

---

*This project was collaboratively developed with clearly defined individual responsibilities.*
