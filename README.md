# Task5
# Heart Disease Classification using Decision Tree and Random Forest

This project demonstrates how to classify heart disease using two tree-based models: **Decision Tree** and **Random Forest**.  
It follows a structured machine learning pipeline including model training, visualization, overfitting analysis, and evaluation using cross-validation.

---

##  Project Structure

- `heart.csv` → Dataset containing patient data and heart disease diagnosis  
- `heart_disease_classification.py` → Main Python script implementing all tasks  

---

##  Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

##  Steps and Implementation

### 1. Train a Decision Tree Classifier and Visualize the Tree
- Built a `DecisionTreeClassifier` using scikit-learn
- Visualized the tree using `plot_tree()` to understand decision rules

### 2. Analyze Overfitting and Control Tree Depth
- Controlled overfitting by adjusting the tree's `max_depth`
- Plotted training vs testing accuracy to visualize the bias-variance tradeoff

### 3. Train a Random Forest and Compare Accuracy
- Trained a `RandomForestClassifier` with 100 trees
- Compared its performance with the Decision Tree on test data

### 4. Interpret Feature Importances
- Extracted and visualized feature importances from the Random Forest model
- Helped identify the most influential features in prediction

### 5. Evaluate Using Cross-Validation
- Performed 5-fold cross-validation using `cross_val_score`
- Reported average accuracy to assess generalization

---

## 📊 Example Output

Decision Tree Accuracy: 0.85
Random Forest Accuracy: 0.91
Cross-Validation Scores: [0.86, 0.88, 0.84, 0.90, 0.87]
Average CV Accuracy: 0.87
