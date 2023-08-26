# CodeClauseInternship_Projects
1. Churn Prediction in Telecom Industry using Logistic Regression:\
   This project uses Logistic Regression to predict churn in the Telecom Industry. Churn rate would refer to the percentage of customers who close their contract or
   subscription with your company in any given time period. I have used a kaggle API for obtaining the .csv file from kaggle *(!kaggle datasets download -d ashishkumarsingh123/telecom-churn-dataset)*.\
   The report of the Logistic regression has the following parts:\
   **Precision:** Precision is a measure of how many of the instances predicted as positive were actually positive.\
   For class 0, the precision is 0.94, indicating that 94% of the instances predicted as class 0 were indeed class 0.\
   For class 1, the precision is 0.48, indicating that 48% of the instances predicted as class 1 were actually class 1.

   **Recall:** Recall, also known as sensitivity or true positive rate, is a measure of how many of the actual positive instances were correctly predicted as positive.\
   For class 0, the recall is 0.96, meaning that 96% of the actual class 0 instances were correctly predicted as class 0.\
   For class 1, the recall is 0.36, indicating that only 36% of the actual class 1 instances were correctly predicted as class 1.

   **F1-Score:** The F1-score is a single metric that balances precision and recall. It gives you an idea of the trade-off between precision and recall.\
   For class 0, the F1-score is 0.95, and for class 1, the F1-score is 0.41.
   
   **Support:** The "support" column indicates the number of instances in each class in your dataset. There are 5476 instances of class 0 and 527 instances of class 1.

   **Accuracy:** The overall accuracy of the model is 0.91, meaning that 91% of the instances in the dataset were correctly classified.

   **Macro Average:** The macro average is the average of precision, recall, and F1-score across all classes.\
   Here, the macro average precision is 0.71, the macro average recall is 0.66, and the macro average F1-score is 0.68.

   **Weighted Average:** The weighted average is similar to the macro average, but it takes into account the class distribution.\
   It's weighted by the number of instances in each class. Here, the weighted average precision is 0.90, the weighted average recall is 0.91, and the weighted average F1-score is 0.90.
