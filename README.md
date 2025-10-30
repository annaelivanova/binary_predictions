# Binary Classification Project (Data Exploration & Modeling)

## Overview
This repository contains a **binary classification project** from a coursework assignment. The goal is to predict a binary target using a dataset with numerical, categorical, and datetime features. The project demonstrates **data preprocessing, model building, fine-tuning, and performance evaluation**.

## Contents
- `binary_classification.ipynb` – Jupyter notebook with preprocessing, model training, and evaluation.  
- `report.pdf` – Detailed project report including methodology, results, and discussion.  

## Key Highlights
- Models tested: **Logistic Regression, Decision Tree, Random Forest**  
- Best model: **Random Forest** (~99% accuracy after fine-tuning)  
- Preprocessing techniques:  
  - Linear Regression for missing values  
  - Weight of Evidence for high-cardinality categorical features  
  - Label encoding and datetime transformation  
  - Feature normalization  

## Figures and Tables
1. **Table 1:** Performance of Logistic Regression, Decision Tree, and Random Forest (default parameters)  
 <img width="403" height="140" alt="image" src="https://github.com/user-attachments/assets/a7b46b4b-8fa9-4deb-8315-4e87d8f28af1" />

2. **Table 2:** Performance of fine-tuned Decision Tree and Random Forest  
 <img width="317" height="114" alt="image" src="https://github.com/user-attachments/assets/4e981c2a-f18b-4605-b0e3-42acd78a4ce6" />

3. **Figure 3:** Confusion matrices for fine-tuned models  
<img width="915" height="361" alt="image" src="https://github.com/user-attachments/assets/04307ff5-f985-4961-82d7-8529040b8521" />


4. **Figure 4:** Feature importance from Decision Tee and Random Forest  
<img width="652" height="219" alt="image" src="https://github.com/user-attachments/assets/22fb9699-e973-4761-9204-1d703601fc2d" />


## Note
⚠️ The dataset used in this project is from the course and cannot be shared. The notebook demonstrates the workflow and methodology.

## License
This repository is licensed under the **MIT License**.

