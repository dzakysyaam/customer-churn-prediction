# Customer Churn Prediction (Logistic Regression)

##  Overview
This project builds a customer churn prediction model using Logistic Regression.  
The objective is to identify at-risk customers and support business retention strategies.

##  Tech Stack
- Python
- Pandas
- Scikit-learn
- Matplotlib

##  Model Performance

### Baseline
- Accuracy: 0.79
- ROC-AUC: 0.83
- Churn Recall: 0.52

### Improved (Class Weight)
- Accuracy: 0.73
- ROC-AUC: 0.83
- Churn Recall: 0.79

Although overall accuracy decreased slightly, churn detection improved significantly, aligning better with business objectives.

##  Business Impact Simulation
Assuming:
- Average monthly revenue: Rp 500,000
- 30% retention success rate

The model could potentially save approximately Rp 44+ million in monthly revenue by identifying high-risk customers.

##  Key Insight
Class weighting and threshold tuning are effective techniques to handle moderate class imbalance without introducing synthetic data.

---

Author: Muhammad Dzaky Syamhaidar
