📖 Overview
This project investigates the impact of social media usage on the academic productivity of university students. Social media is an integral part of modern student life, but its effect on academic performance is ambiguous. This study employs various machine learning classification models to predict this impact based on factors like daily usage hours, purpose of use, and frequency of interaction.

The target variable, "Impact on Academic Productivity," is categorized into:

Positive

Strong Positive

Negative

Strong Negative

Neutral

📊 Dataset
The dataset is a primary, live collection of responses from students at Metropolitan University, Sylhet.

Source: Collected via a Google Form shared with juniors, seniors, and batchmates.

Size: 400+ entries with 15 features.

Key Features:

Age

Gender

Study Hours

Most Used Social Media Platform (Facebook, Instagram, YouTube, etc.)

Primary Purpose for Using Social Media (Entertainment, Academic)

Average Daily Social Media Usage (hrs)

Frequency of Checking Social Media (Frequently, Occasionally)

Time Spent per Session (mins)

Frequency of Using Social Media for Academic Purpose (Rare, Sometimes, Most of the time)

Contribution to Study (Yes, No)

Study/Assignment Completion Rate (Always on time, Frequently delayed)

Feeling of Laziness After Using Social Media (Yes, No)

Usage of Social Platform Before Sleep (Yes, No)

Preferred Time (Morning, Afternoon, Evening, Night)

Impact on Academic Productivity (Target Variable)

🔍 Exploratory Data Analysis (EDA) - Key Insights
Gender Distribution: 55.69% Male, 44.31% Female.

Top Platforms: Facebook (274), Instagram (208), and YouTube (165) dominate usage.

Primary Purpose: Vast majority (362 users) use social media for Entertainment vs. Academic (42 users).

Daily Usage: Most users spend 4-5 hours daily on social media.

Academic Use: Most users (243) use social media for academic purposes only "Sometimes".

Preferred Time: Night (291 users) is the most preferred time for social media activity.

Overall Impact: The most common reported impact is Neutral (171 users), followed by Positive (114) and Negative (73).

🛠️ Methodology & Models
The problem was approached as a multi-class classification task. The following machine learning models were implemented and evaluated:

Logistic Regression

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Techniques for Performance Improvement:
Hyperparameter Tuning: Significantly improved Logistic Regression (from 53% to 80% accuracy) and Decision Tree models.

Data Augmentation (SMOTE): Applied to handle class imbalance, resulting in improved F1 scores for most models.

Ensemble Learning (Voting Classifier): Combined base models to achieve better generalizability and performance (e.g., Logistic Regression accuracy improved from 53% to 71%).

📈 Results and Evaluation
Final Model Performance (After Tuning & Augmentation):
Model	Accuracy	Precision	Recall	F1 Score
Logistic Regression	80%	-	-	68%
SVM	80%	-	80%	88%
KNN	68%	81%	68%	68%
Decision Tree	75%	-	-	62%
Random Forest	68%	70%	65%	68%
🚀 Future Work
Potential directions for enhancing this project include:

Expanding Dataset: Collect more data from diverse regions, institutions, and academic disciplines.

Incorporating New Features: Add features like stress levels, time management strategies, and type of content consumed.

Advanced Models: Experiment with algorithms like XGBoost, LightGBM, or Neural Networks.

Longitudinal Study: Track changes in social media usage and academic impact over time.

Platform-Specific Analysis: Deep dive into how specific platforms (e.g., YouTube vs. Instagram) affect productivity differently.

Sentiment Analysis: Analyze the sentiment of social media content to correlate with academic performance.

📝 Conclusion
This project successfully built a predictive framework to assess social media's influence on academics. While initial model performances were moderate, techniques like hyperparameter tuning and data augmentation led to substantial improvements. The analysis provides valuable insights into student behavior and highlights the complex, often neutral-to-negative relationship between high social media usage and academic productivity. The framework serves as a foundation for more extensive research in this domain.

👥 Contributors
Ashraful Quaiyum Chowdhury Shafi (221-115-118) - 56th Batch, Section C

Jarin Tasnim Ahmed Raisa - 56th Batch, Section D

Department of Computer Science and Engineering
Metropolitan University, Sylhet.
