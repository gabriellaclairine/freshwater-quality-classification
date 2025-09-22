# 💧 Freshwater Data Quality Classification

This project builds a **machine learning classifier** to predict the **Data Quality** of freshwater measurements using diverse environmental, method, and station features.  
The notebook covers **data exploration, preprocessing, encoding, model training, and evaluation**.

---

## ⚙️ Project Workflow

1. **Data Exploration & Cleaning**  
   - Inspected data structure, missing values, and class distribution.  
   - Handled categorical and numerical features.  
   - Addressed missingness through imputation.  

2. **Feature Engineering**  
   - Encoded categorical variables with appropriate techniques.  
   - Normalized/scaled continuous variables.  
   - Balanced the dataset using resampling strategies.  

3. **Modeling**  
   - Trained baseline models (e.g., Logistic Regression, Random Forest, Gradient Boosting).  
   - Applied cross-validation for robust evaluation.  
   - Tuned hyperparameters to optimize performance.  

4. **Evaluation**  
   - Measured results using **macro-F1 score**.  
   - Compared per-class precision, recall, and F1 across labels (`Good`, `Fair`, `Unknown`, `Pending Review`).  
   - Visualized confusion matrix and classification metrics.  

---

## 📈 Results and Conclusion

- The models achieved solid predictive performance on the test set.  
- Macro-F1 highlighted the importance of handling minority classes (`Unknown`, `Pending Review`).  
- Tree-based ensemble methods outperformed simpler baselines. 
