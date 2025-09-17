# Global Plastic Waste Monitoring (WEKA-Based Project)

## Introduction
This project focuses on monitoring global plastic waste and analyzing its impact on the environment.  
The work was carried out using **WEKA**, a machine learning toolkit, to preprocess the dataset, train models, and evaluate results.  
This repository contains the main code file (`source_code.py`) which documents the workflow and project methodology.

---

## Project Workflow
1. **Dataset (Week 1)**  
   - Collected and preprocessed plastic waste dataset.  
   - Saved in ARFF format for use in WEKA.  

2. **Model Training (Week 2)**  
   - Multiple ML models were trained in WEKA (Decision Tree, Random Forest, Logistic Regression).  
   - Random Forest performed the best.  

3. **Evaluation (Week 3)**  
   - Accuracy, Precision, Recall, and F1-score were measured.  
   - Confusion matrix and classification report were analyzed.  
   - Random Forest was finalized as the best model.  

---

## Repository Contents
- `source_code.py` → Main project code (wrapper script).  
- *(Optional)* Dataset (`.arff`), saved model (`.model`), and evaluation results (`.txt`) were also generated in WEKA but are not required for this final submission.  

---

## Results
- **Best Model:** Random Forest  
- **Accuracy:** ~92% (better than Decision Tree and Logistic Regression)  
- **Reason for Selection:** Provides stable predictions and works well on categorical + numerical attributes.  

---

## Future Scope
- Integration with live environmental sensors.  
- Real-time dashboards for visualization.  
- Deployment as a web or mobile application.  

---

## Conclusion
This project demonstrates how plastic waste monitoring can be supported using machine learning tools like WEKA.  
Random Forest was identified as the most suitable model, and this repository provides the code reference for the workflow followed during the project.
