# Monitoring Project using WEKA

## ✅ Project Overview
This project demonstrates a step-by-step **data analysis and model building workflow** using WEKA.  
It covers:  
1. **Dataset preprocessing**  
2. **Model training and evaluation**  
3. **Selecting the best model based on accuracy**

## 📂 Week 1: Dataset Preparation
**Files included:**  
- `Plastic Waste Around the World.csv` – Original dataset downloaded.  
- `Plastic Waste_week_1.arff` – Dataset after preprocessing in WEKA (missing values handled, attributes formatted, etc.).

**Steps performed:**  
1. Import CSV into WEKA.  
2. Preprocess dataset (remove irrelevant attributes, handle missing values).  
3. Export cleaned dataset to ARFF format for modeling.

## 📂 Week 2: Model Training
**Files included:**  
- `.model` files – Saved WEKA model files.  
- Screenshots showing model training and **accuracy comparisons**.

**Steps performed:**  
1. Load the cleaned ARFF dataset.  
2. Train multiple models (e.g., tress.M5P , Random Forest, Naive Bayes).  
3. Compare model accuracies using WEKA evaluation metrics.  
4. Save the trained models for later evaluation.


## 📂 Week 3: Evaluation
**Files included:**  
- `evaluation_results.txt` – Exported from WEKA result buffer.  
- Optional confusion matrix screenshots.  
- Short summary report explaining **why the best model was chosen**.

**Steps performed:**  
1. Load saved models and evaluate on test data.  
2. Analyze accuracy, precision, recall, F1-score, and confusion matrix.  
3. Select the best-performing model.  
4. Document reasoning in the summary report.

## 📝 Summary
- Preprocessing ensures **clean and usable data**.  
- Model training identifies **most accurate predictive model**.  
- Evaluation confirms the **best model for deployment or prediction tasks**.


## 📁 File Structure
