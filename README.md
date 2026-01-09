# ML-Based Employee Attrition and Performance Analysis

##  Project Summary
This project focuses on predicting employee performance and analyzing how it impacts employee attrition.  
Using a real-world HR dataset, multiple machine learning models were trained and evaluated to identify the most effective approach for early attrition detection.



## Dataset Details
- Dataset Size: 10,000 employee records
- Feature Types: Demographic, professional, workload, behavioral
- Target: Employee Attrition
- Final Feature Count: 41



##  Preprocessing Pipeline
- Data cleaning and validation
- Encoding categorical variables
- Feature engineering using domain knowledge
- Correlation analysis
- SMOTE for class imbalance
- Pipeline-based model training

###  Cleaned Dataset Preview
preproccesed_dataset.png

##  Machine Learning Models
- Logistic Regression (Baseline)
- Random Forest
- XGBoost
- Multi-Layer Perceptron (MLP)
- Voting Ensemble Classifier



##  Performance Comparison

| Model | Accuracy | F1-Macro |
|------|---------|----------|
| Logistic Regression | 24.8% | 0.247 |
| Random Forest | 69.1% | 0.669 |
| XGBoost | 80.0% | 0.790 |
| MLP | **93.0%** | **0.9297** |
| Voting Ensemble | 85.7% | 0.853 |

##  Confusion Matrices

### Logistic Regression  
<img src="confusion_matrix1.png" width="300"/>

### Random Forest  
<img src="confusion_matrix2.png" width="300"/>

### XGBoost  
<img src="confusion_matrix3.png" width="300"/>

### MLP Neural Network  
<img src="confusion_matrix4.png" width="300"/>


### Voting Ensemble  
<img src="confusion_matrix5.png" width="300"/>



##  Insights
- Linear models fail to capture complex employee behavior
- Neural networks excel at modeling performance-related patterns
- Performance decline is a strong early indicator of attrition
- Ensemble learning improves robustness and generalization



## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- PyTorch
- SMOTE (imbalanced-learn)
- Matplotlib / Seaborn



##  Conclusion
Machine learning can effectively predict employee performance and provide actionable insights into attrition risk.  
This system can support HR decision-making and workforce planning.


