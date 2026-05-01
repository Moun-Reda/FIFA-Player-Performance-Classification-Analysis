# FIFA Player Performance Classification & Analysis (Team Project)

## 📌 Project Context
This project was developed as a collaborative team effort to analyze FIFA player data and predict market values and performance tiers. 

## 🛠️ My Specific Contributions
While this was a group project, my role focused on the **Classification and Naïve Bayes Analysis** segment. My contributions included:

*   **Target Engineering:** Defined performance tiers (Low, Mid, High, Elite) using percentile-based thresholds (25th, 60th, 90th) to handle class distribution.
*   **Model Implementation:** Implemented and compared multiple Naïve Bayes variants:
    *   **GaussianNB:** Applied to numerical features like `Age`, `Potential`, and `Total_Stats`.
    *   **BernoulliNB:** Used for binary categorical features (One-Hot Encoded positions).
    *   **ComplementNB:** Specifically implemented to address class imbalance issues within the performance tiers.
*   **Evaluation & Visualization:** Conducted detailed error analysis using **Confusion Matrices** and **Classification Reports** (Precision, Recall, F1-Score) to determine the most effective model.
*   **Insight Generation:** Proved that scaling does not impact GaussianNB performance due to its reliance on distribution mean and variance.

## 🚀 Key Technical Insights (from my part)
*   **GaussianNB** emerged as the most appropriate model for this dataset, achieving the highest accuracy for player tier classification.
*   Analyzed the impact of feature scaling on probabilistic models, concluding its neutrality for Gaussian distributions in this context.

## 💻 Technologies Used (My Module)
*   Python, Pandas, NumPy
*   Scikit-Learn (GaussianNB, BernoulliNB, ComplementNB)
*   Seaborn & Matplotlib for Confusion Matrix visualization
