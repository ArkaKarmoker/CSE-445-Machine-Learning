# CSE-445-Machine-Learning

# Prediction of Injury Type and Patient Status in Road Traffic Accidents using Machine Learning.
**Group Name:** ML Mavericks  
**Course:** CSE445 - Machine Learning  
**Faculty:** Mirza Mohammad Lutfe Elahi [MLE]  
**Department:** Electrical and Computer Engineering (ECE)  
**University:** North South University  

## Project Overview  
This project was completed as part of the CSE445 Machine Learning course. The goal was to build and evaluate machine learning models to predict injury types and patient statuses based on a provided dataset. The project was divided into four phases, covering data preprocessing, model training, and performance evaluation.

### Dataset  
**Dataset Name:** RTA Data 2020 to July 2023  
**Source:** [Dataverse Harvard - RTA Data 2020 to July 2023](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/4VGTDRLinks)  

---

## Phase 01: Data Preprocessing  

### Task:  
- Apply data preprocessing techniques to clean and prepare the dataset.  
- Handle missing values, encode categorical features, and split the dataset for model training and testing.  

**Submission Type:** Jupyter Notebook (.ipynb)  
**File Name:** [Group Name].ipynb  

---

## Phase 02: Logistic Regression Model  

### Tasks:  
1. Apply data preprocessing (refined and extended from Phase 01).  
2. Train Logistic Regression models for two targets: **Injury Type** and **Patient Status**.  
3. Test the trained models on the test set.  
4. Evaluate model performance using:  
   - Accuracy  
   - Confusion Matrix  
   - Precision  
   - Recall  
   - F1 Score  
5. Plot learning curves:  
   - Accuracy vs Solver  
   - Accuracy vs Max Iterations  

**Solvers Used:** {'lbfgs', 'liblinear', 'newton_cg', 'newton-cholesky', 'sag', 'saga'}  
**Max Iterations:** {50, 100, 150, 200, 250, 300}  
**Submission Type:** Jupyter Notebook (.ipynb) with outputs  

---

## Phase 03: Advanced Model Training and Evaluation  

### Tasks:  
1. Apply necessary data preprocessing.  
2. Train the following models on the train set:  
   - Decision Tree  
   - Random Forest  
   - XGBoost  
   - Support Vector Machine (SVM)  
3. Evaluate performance using:  
   - Accuracy  
   - Precision  
   - F1 Score  
   - Recall  
   - Confusion Matrix  
4. Compare models against Logistic Regression (from Phase 02) and prepare a performance table.  
5. Plot learning curves:  
   - **Decision Tree:** Accuracy vs Max Depth  
   - **SVM:** Accuracy vs Kernel  
   - **Random Forest:** Accuracy vs Number of Estimators  
   - **XGBoost:** Accuracy vs Learning Rate  

**Hyperparameters:**  
- **Decision Tree:** Max Depth = {4, 5, 6, 7, 8, 9}  
- **SVM:** Kernel = {'linear', 'poly', 'rbf', 'sigmoid'}  
- **Random Forest:** N_estimators = {10, 50, 100, 200}  
- **XGBoost:** Learning Rate = {0.001, 0.01, 0.1, 1}  

---

## Phase 04: Artificial Neural Network (ANN)  

### Tasks:  
1. Apply necessary data preprocessing.  
2. Train an Artificial Neural Network (ANN) on the train set.  
3. Evaluate model performance using:  
   - Accuracy  
   - Precision  
   - F1 Score  
   - Recall  
   - Confusion Matrix  
4. Prepare a performance comparison table including all models:  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - XGBoost  
   - SVM  
   - ANN  
5. Visualize and compare performance metrics across models.  
6. Write a final report using the IEEE template.  

**Template:** [IEEE Conference Publishing Templates](https://www.ieee.org/conferences/publishing/templates.htmlLinks)  

---

## Final Submission  
- **Deliverables:**  
   - Jupyter Notebooks (Phase-wise)  
   - Visualizations and plots  
   - Comparison tables  
   - Final report (IEEE template)  
- **Viva:**

---

## How to Run the Project  
1. Clone the repository.  
2. Install required packages.  
3. Open the Jupyter Notebooks and execute the cells of ML_Maverics.ipynb sequentially.  
4. Visualize the output and analyze the performance metrics.  

---

## Acknowledgments  
Special thanks to instructor and group members for their support throughout the project.

