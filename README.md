
# SMS Spam Detection Using Machine Learning

## 1. Project Overview
SMS Spam Detection is a machine learning project that classifies text messages into two categories: Spam and Ham (legitimate messages). The main objective is to identify unwanted or fraudulent messages automatically using machine learning algorithms.

## 2. Problem Statement
SMS spam messages may contain fraudulent links, advertisements, or misleading offers. Manually identifying these messages is time-consuming. This project develops a machine learning system to classify SMS messages automatically and help users identify potentially unwanted messages.

## 3. Objectives
- Analyze and preprocess SMS messages.
- Convert text into numerical features using TF-IDF.
- Implement four machine learning algorithms.
- Compare model performance using evaluation metrics.
- Identify a suitable model for spam detection.

## 4. Dataset
The project uses the SMS Spam Collection dataset from the UCI Machine Learning Repository.

Dataset link: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

The dataset contains messages labelled as:
- **Ham:** Legitimate SMS messages.
- **Spam:** Unwanted or potentially fraudulent SMS messages.

## 5. Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- Matplotlib

## 6. Methodology
1. Load and inspect the SMS dataset.
2. Remove duplicate and missing records.
3. Clean and normalize the message text.
4. Split the dataset into training and testing sets.
5. Convert text into numerical features using TF-IDF.
6. Train and test four machine learning classifiers.
7. Evaluate performance using accuracy, precision, recall, F1-score, runtime, and confusion matrices.
8. Perform a what-if experiment by changing the K value in K-Nearest Neighbours (KNN).
9. Compare the results and interpret the findings.

## 7. Machine Learning Algorithms
- **Decision Tree:** Classifies messages using decision rules.
- **K-Nearest Neighbours (KNN):** Predicts the class based on neighbouring training samples.
- **Support Vector Machine (SVM):** Separates classes using a decision boundary.
- **Multinomial Naive Bayes:** Uses word-feature probabilities to classify messages.

## 8. Evaluation Metrics
- **Accuracy:** Overall proportion of correct predictions.
- **Precision:** Proportion of predicted spam messages that are actually spam.
- **Recall:** Proportion of actual spam messages detected.
- **F1-score:** Harmonic mean of precision and recall.
- **Runtime:** Time taken for model training and prediction.
- **Confusion matrix:** Shows correct and incorrect classifications.

## 9. Experimental Analysis
The four classifiers are evaluated using the same training and testing split. Their results are compared using evaluation metrics and visualizations. A KNN parameter experiment investigates how changing the number of neighbours affects classification performance.

The best-performing model will be selected based on the actual experimental results, with particular attention to spam recall and F1-score.

## 10. Conclusion
This project demonstrates how machine learning can be used to classify SMS messages as spam or legitimate. Comparing multiple classifiers helps identify the most suitable model for the selected dataset. The experiment also illustrates the importance of preprocessing, feature extraction, evaluation metrics, and parameter tuning.

## 11. Limitations
- The model is trained on a particular SMS dataset.
- New spam patterns may reduce performance on unseen messages.
- The dataset may not represent every language or messaging style.
- Evaluation results depend on the dataset and experimental setup.

## 12. How to Run
1. Open `SMS_Spam_Classification.ipynb` in Google Colab.
2. Download the dataset from the UCI repository.
3. Upload and extract the dataset as required by the notebook.
4. Run the code cells in order.
5. Review the comparison table, graphs, and confusion matrices.

## 13. Author
Name: [Your Name]

Register Number: [Your Register Number]

Institution: SRM Institute of Science and Technology, Tiruchirappalli
