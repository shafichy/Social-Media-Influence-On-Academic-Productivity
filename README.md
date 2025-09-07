# Social Media Influence on Academic Productivity

![Machine Learning](https://img.shields.io/badge/Machine-Learning-blue) ![Classification](https://img.shields.io/badge/Task-Classification-green) ![Python](https://img.shields.io/badge/Language-Python-yellow)

##  Overview

This project investigates the impact of social media usage on the academic productivity of university students. **The goal is to predict the impact (Positive, Negative, Neutral, etc.) based on usage patterns.**

##  Dataset

**The dataset is a primary, live collection of responses from students at Metropolitan University, Sylhet,** including juniors, seniors, and batchmates.

-   **Source:** Collected via a Google Form.
-   **Size:** **400+ entries** with **15 features**.
-   **Key Feature:** The target variable is **`Impact on Academic Productivity`** (Positive, Strong Positive, Negative, Strong Negative, Neutral).

##  Exploratory Data Analysis (EDA) - Key Insights

-   **Top Platforms:** **Facebook, Instagram, and YouTube** dominate usage.
-   **Primary Purpose:** Vast majority use social media for **Entertainment (362 users)** vs. Academic (42 users).
-   **Daily Usage:** Most users spend **4-5 hours** daily on social media.
-   **Overall Impact:** The most common reported impact is **Neutral (171 users)**.

##  Methodology & Models

The problem was approached as a **multi-class classification task**. Implemented models:

1.  Logistic Regression
2.  Support Vector Machine (SVM)
3.  K-Nearest Neighbors (KNN)
4.  Decision Tree
5.  **Random Forest**

### Techniques for Performance Improvement:
-   **Hyperparameter Tuning:** **Improved Logistic Regression from 53% to 80% accuracy.**
-   **Data Augmentation (SMOTE):** Applied to handle class imbalance.
-   **Ensemble Learning (Voting Classifier):** Combined models for better performance.

##  Results and Evaluation

### Final Model Performance (After Tuning & Augmentation):

| Model               | Accuracy | Precision | Recall | F1 Score |
| :------------------ | :------- | :-------- | :----- | :------- |
| Logistic Regression | 80%      | -         | -      | 68%      |
| SVM                 | 80%      | -         | 80%    | 88%      |
| KNN                 | 68%      | 81%       | 68%    | 68%      |
| Decision Tree       | 75%      | -         | -      | 62%      |
| Random Forest       | 68%      | 70%       | 65%    | 68%      |

**Conclusion: SVM achieved the highest F1 Score (88%), while Logistic Regression achieved the highest tuned Accuracy (80%).**

##  Future Work

Potential directions for enhancing this project include:
1.  **Expanding Dataset** from diverse regions and disciplines.
2.  **Incorporating New Features** like stress levels and content type.
3.  **Using Advanced Models** like XGBoost or Neural Networks.

##  Conclusion

This project built a predictive framework to assess social media's influence on academics. **Techniques like hyperparameter tuning led to substantial improvements,** providing a foundation for more extensive research.

##  Contributors

-   **Ashraful Quaiyum Chowdhury Shafi** (221-115-118)
-   **Jarin Tasnim Ahmed Raisa** (221-115-124)

**Department of Computer Science and Engineering**  
**Metropolitan University, Sylhet.**

---

