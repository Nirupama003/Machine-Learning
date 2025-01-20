#1.Molecular Solubility Prediction Using Machine Learning 🌟

## Project Overview  
This project aims to predict the solubility of molecules using their molecular descriptors. By leveraging machine learning techniques, we compare the performance of two models: **Linear Regression** and **Random Forest Regressor**.  

Molecular solubility prediction is a critical task in industries such as **pharmaceuticals** and **chemical engineering**, where solubility plays a vital role in drug formulation and chemical processing.

---

## Dataset  
We used the **Delaney solubility dataset** (`delaney_solubility_with_descriptors.csv`), which includes:  
- Molecular descriptors (independent variables).  
- Solubility values (logS) as the target variable.  

---

## Project Workflow  

1. **Data Preprocessing**:  
   - Cleaned and prepared the dataset to ensure it is suitable for modeling.  
   - Handled missing values and scaled features where necessary.  

2. **Model Development**:  
   - **Linear Regression**: Built a baseline model for comparison.  
   - **Random Forest Regressor**: Developed a more complex ensemble model to capture non-linear relationships.  

3. **Evaluation & Comparison**:  
   - Used **Mean Squared Error (MSE)** and **R² Score** to evaluate model performance.  
   - Compared the models to determine trade-offs between simplicity and accuracy.  

---

## Results  
| Metric                | Linear Regression | Random Forest Regressor |  
|-----------------------|-------------------|-------------------------|  
| **Mean Squared Error** | 1.0207           | 1.4077                  |  
| **R² Score**          | 0.7892            | 0.7092                  |  

---

## Key Takeaways  
- **Linear Regression**: Provided a simple, interpretable baseline model with decent performance.  
- **Random Forest Regressor**: Achieved better performance by capturing complex, non-linear patterns in the data.  
- **Applications**: Insights from this project can aid in drug discovery, formulation design, and chemical process optimization.

---

## Tools & Technologies  
- **Programming Language**: Python  
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn  

---

## Acknowledgments  
This project was inspired by a YouTube tutorial. Thanks to the creator for providing guidance and a foundation to build upon.  

---
