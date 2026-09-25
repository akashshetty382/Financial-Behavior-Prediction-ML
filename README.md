 Financial Habits ML Prediction



## Project Overview
This repository contains the complete Laboratory Experiment and machine learning pipeline for Assignment 2. The project performs Exploratory Data Analysis (EDA) and predictive modeling on a self-reported financial habits dataset. The primary objective is to classify and predict budgeting behavior based on demographic and behavioral survey responses, bridging the gap between attitudinal survey data and machine learning classification.

## Repository Structure
* **`financial_habits_survey01.csv`**: The primary dataset containing survey responses regarding budgeting, spending, saving, and investment confidence.
* **`description.pdf`**: The data dictionary detailing all dataset features and their respective ordinal or nominal scales.
* **`PMIOTuML_Assign2.ipynb`**: The main Google Colab notebook containing all source code for data cleaning, preprocessing, exploratory data analysis, model training, and evaluation.
* **`README.md`**: Project documentation and results comparison.

## Methodology
1. **Data Preprocessing & Encoding:** Handled missing categorical values via mode imputation. Mapped lengthy survey question columns to concise programmatic variables. Applied Label Encoding to nominal variables and Ordinal Encoding to ranked behavioral responses (e.g., frequency of impulse purchases).
2. **Exploratory Data Analysis (EDA):** Visualized demographic distributions, evaluated the interaction between budgeting adherence and impulse purchasing, and generated a correlation heatmap to identify collinearity among behavioral traits.
3. **Machine Learning Implementation:** Split the dataset to predict `follows_budget` as the target variable. Evaluated classical and ensemble classifiers to benchmark performance on non-transactional behavioral data.

## Results & Literature Comparison
As outlined in the Assignment 1 Literature Review, the models implemented in this experiment are benchmarked against the baseline results reported in **Paper 20: *Financial Customer Behavior Prediction Based on Machine Learning: A Comprehensive Investigation***. 

| Machine Learning Model | My Implementation (Accuracy / F1) | Paper 20 Baseline (Accuracy / F1) |
| :--- | :--- | :--- |
| **K-Nearest Neighbours** | `[Insert your %]` | `[Insert Paper 20 %]` |
| **Decision Tree** | `[Insert your %]` | `[Insert Paper 20 %]` |
| **Gaussian Naive Bayes** | `[Insert your %]` | `[Insert Paper 20 %]` |
| **Logistic Regression** | `[Insert your %]` | `[Insert Paper 20 %]` |
| **Random Forest (Ensemble)** | `[Insert your %]` | `[Insert Paper 20 %]` |
| **AdaBoost (Ensemble)** | `[Insert your %]` | `[Insert Paper 20 %]` |
| **Gradient Boosting (Ensemble)**| `[Insert your %]` | `[Insert Paper 20 %]` |

### Summary of Findings
* *[Insert 1-2 sentences summarizing which model performed best on your dataset.]*
* *[Insert 1-2 sentences explaining how your results compare to the theoretical benchmarks set by Paper 20. Did your ensemble models outperform the classical ones, as suggested by the literature?]*

## How to Run
1. Open `PMIOTuML_Assign2.ipynb` in Google Colab.
2. Run the first cell to trigger the file upload prompt.
3. Upload `financial_habits_survey01.csv`.
4. Select **Runtime > Run all** to execute the pipeline and generate the evaluation metrics.
