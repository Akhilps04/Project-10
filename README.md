# Shrimp Quality Classification using Hybrid Machine Learning Models
This project focuses on developing a hybrid machine learning model to classify shrimp quality as either "Good" or "Bad" based on environmental and transport data. The model combines the strengths of Random Forest, Gradient Boosting, and SVM classifiers to achieve reliable predictions.

# Key Features
Dataset: A shrimp quality dataset, including variables like environmental factors and transport type (Air Conditioned or Open Air).
Models Used:
Random Forest
Gradient Boosting
SVM
Hybrid Approach: Averages probabilities from the three models to form an ensemble, improving overall accuracy.
Performance Highlights:
Gradient Boosting: 99.4% accuracy
Random Forest: 98.95% accuracy
SVM: 78.05% accuracy
Hybrid Model: 98.5% accuracy

# Project Workflow
Data Preprocessing
Handled encoding of categorical variables.
Performed train-test split with stratification for balanced evaluation.
Model Training
Individual models (Random Forest, Gradient Boosting, SVM) trained on the shrimp quality dataset.
Hybrid Model
Combined predictions from all three classifiers to produce a robust hybrid solution.
Evaluation Metrics
Accuracy
Confusion Matrix
ROC Curve
Cross-Validation
Feature Importance Analysis
Identified and visualized key features influencing predictions.

# Project Results
Model-wise Accuracy:
Random Forest: 98.95%
Gradient Boosting: 99.4%
SVM: 78.05%
Hybrid Model: 98.5%
Cross-Validation Accuracy:
Random Forest: 98.69%
Gradient Boosting: 99.3%
SVM: 77.54%
Visual Insights:
Confusion Matrix and ROC Curve highlight the hybrid model's strong performance.
Feature importance analysis shows which variables most impact classification.

# Future Improvements
Collect more diverse data samples to improve generalizability.
Implement feature selection techniques to refine the model further.
Explore the integration of deep learning architectures for classification.
Automate the entire pipeline for real-time classification.

# Acknowledgements
This project was made possible by the contributions of the team and the availability of the shrimp quality dataset. Special thanks to mentors for their valuable guidance.

## 📄 License
This project is for academic and demonstration purposes only. Please credit the authors if reused or modified.
