# Water-Quality-Prediction-using-Machine-Learning-and-Deep-Learning-Approaches
This project predicts water potability using Machine Learning and Deep Learning models. We used Logistic Regression, Random Forest, and a Deep Neural Network with ReLU activations. Data imbalance was handled with SMOTE. Models were evaluated with accuracy, precision, recall, F1-score.

# Water Quality Prediction

This project predicts whether water is **potable (safe to drink)** or **non-potable** using Machine Learning and Deep Learning models.  
We used **Logistic Regression, Random Forest, and a Deep Neural Network**, with data imbalance handled using **SMOTE**.  
Models were evaluated using **accuracy, precision, recall, F1-score, and ROC-AUC**.  

##  Models Used
- Logistic Regression (baseline)  
- Random Forest Classifier (best performer)  
- Deep Neural Network (128 → 64 → 32 → 16 → 1)  

##  Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn tensorflow

