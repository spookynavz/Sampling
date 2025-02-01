# Sampling Assignment

**Submitted By**: Navyaa
**Roll No.**: 102203276 
**Group**: 3C52 

## Overview
This Python Notebook evaluates the accuracy of **5 different models** across **5 different samples** created using various sampling techniques.

### Models Used:
1. Naive Bayes  
2. Logistic Regression  
3. K-Nearest Neighbours  
4. Support Vector Machine  
5. Decision Tree  

### Sampling Techniques:
1. Random Sampling  
2. Stratified Sampling  
3. Cluster Sampling  
4. Oversampling  
5. Undersampling  

---

## Results
The table below shows the accuracy of each model on the different sampling techniques:

| **Model**               | **Random Sampling** | **Stratified Sampling** | **Cluster Sampling** | **Oversampling** | **Undersampling** |
|--------------------------|---------------------|--------------------------|-----------------------|------------------|-------------------|
| **Naive Bayes**          | 0.765027            | 0.836066                 | 0.873362              | 0.812227         | 0.882096         |
| **Logistic Regression**  | 0.907104            | 0.896175                 | 0.927948             | 0.910480         | 0.893013          |
| **K-Nearest Neighbours** | 0.775956            | 0.765027                 | 0.842795             | 0.812227         | 0.814410         |
| **Support Vector Machine** | 0.693989          | 0.704918                 | 0.676856              | 0.679039         | 0.661572          |
| **Decision Tree**        | **0.989071**            | 0.950820                 | 0.984716          | 0.984716     | 0.975983          |

---

### Key Insights:
- The **best accuracy achieved** is **0.989071**, using the **Decision Tree model** with both:
  - **Random Sampling**    

> **Note**: The accuracy may vary for different rows picked when generating a sample.

---

## Final Output
The final table of results can be found at the end of the Python Notebook.  
