# Sampling Techniques on Imbalanced Credit Card Dataset

- **Name:** Ananya  
- **Roll Number:** 102303160  

## Objective

The objective of this assignment is to understand the importance of **sampling techniques** in handling **imbalanced datasets** and to analyze how different sampling strategies affect the performance of various machine learning models.

##  Dataset

The dataset used in this assignment is a **highly imbalanced credit card fraud dataset**, where:

- **Class 0** → Non-fraudulent transactions  
- **Class 1** → Fraudulent transactions  

**Dataset Source:**  
https://github.com/AnjulaMehto/Sampling_Assignment/blob/main/Creditcard_data.csv

##  Problem Statement

In real-world applications, imbalanced datasets can significantly affect machine learning performance.  
This assignment focuses on:

- Converting an imbalanced dataset into a balanced dataset  
- Applying multiple sampling techniques  
- Training multiple machine learning models  
- Evaluating the impact of sampling on model accuracy  

## Sampling Techniques Used

1. **Sampling1** – Random Over Sampling  
2. **Sampling2** – Random Under Sampling  
3. **Sampling3** – SMOTE  
4. **Sampling4** – SMOTETomek  
5. **Sampling5** – SMOTEENN  

## Machine Learning Models Used

- **M1** – Logistic Regression  
- **M2** – Decision Tree Classifier  
- **M3** – Random Forest Classifier  
- **M4** – Support Vector Machine (SVM)  
- **M5** – Naive Bayes Classifier  

---

## Experimental Setup

- Dataset split into **70% training** and **30% testing**
- Feature scaling performed using **StandardScaler**
- Sampling techniques applied only on training data
- Model performance evaluated using **Accuracy (%)**

## Final Results

###  Best Sampling Technique for Each Model
<img width="575" height="295" alt="image" src="https://github.com/user-attachments/assets/50b89526-d0ef-4514-a197-8c82af35c590" />


## Analysis and Discussion

- **Sampling1 (Random Over Sampling)** achieved the highest accuracy for **four out of five models**, making it the most consistent sampling technique.
- **Sampling5 (SMOTEENN)** performed best for **Logistic Regression**, indicating effective handling of noise and overlapping classes.
- Ensemble models like **Random Forest** showed excellent performance after oversampling due to better minority-class representation.

## Conclusion

Handling class imbalance is crucial for achieving reliable machine learning performance.  
Among all evaluated techniques, **Random Over Sampling (Sampling1)** proved to be the most effective and consistent across different models for this dataset.

## Repository Structure

```text
Sampling/
│
├── Sampling.ipynb
├── README.md
