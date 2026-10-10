
# MainCrafts AIML Internship — Task 2

## AI/ML Model Comparison Using California Housing Dataset

### Project Overview
This project compares three machine learning regression algorithms to predict California housing values using the California Housing dataset.

The objective is to evaluate the models and identify the best-performing model using standard regression evaluation metrics.

### Dataset
- **Dataset:** California Housing
- **Source:** Scikit-learn built-in dataset
- **Total records:** 20,640
- **Features:** 8 input features
- **Target:** Median house value
- **Training split:** 80%
- **Testing split:** 20%

### Technologies Used
- Python
- Jupyter Notebook in Visual Studio Code
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Methodology
1. Load the California Housing dataset.
2. Explore the dataset and check for missing values.
3. Perform exploratory data analysis.
4. Split the data into training and testing sets.
5. Standardize the input features using StandardScaler.
6. Train and compare Linear Regression, Ridge Regression, and Decision Tree Regression models.
7. Evaluate the models using MAE, RMSE, and R² score.
8. Visualize actual versus predicted housing values.
9. Identify the best-performing model.

### Model Comparison Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Decision Tree | 0.4267 | 0.6563 | 0.6713 |
| Ridge Regression | 0.5332 | 0.7456 | 0.5758 |
| Linear Regression | 0.5332 | 0.7456 | 0.5758 |

### Conclusion
The Decision Tree Regression model performed best among the three evaluated models. It achieved the lowest RMSE of 0.6563 and the highest R² score of 0.6713.

The results indicate that the Decision Tree model provided better predictions on the test dataset than the two linear models in this experiment.

### Project Files
- `AI_ML_Task2_Model_Comparison.ipynb` — Notebook containing the analysis, model training, evaluation, and visualizations.
- `model_comparison_results.csv` — CSV file containing the model comparison metrics.
- `README.md` — Project documentation.
- `MainCrafts_AIML_Task2_Report.pdf` — Project report.

### Internship
**Organization:** MainCrafts Technology  
**Domain:** Artificial Intelligence and Machine Learning  
**Task:** Task 2 — AI/ML Model Comparison
