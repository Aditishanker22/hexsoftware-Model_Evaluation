Classification Report Summary — Breast Cancer Model Evaluation

The Breast Cancer Classification model was evaluated using the testing dataset, and the results show that the model performs exceptionally well. Several performance metrics—including accuracy, precision, recall, and F1-score—were calculated, along with a confusion matrix and classification report to understand the model’s strengths and weaknesses.

✅ Overall Performance Metrics
Metric	Score
Accuracy	0.9736
Precision	0.9722
Recall	0.9859
F1-Score	0.9790

These values indicate very high predictive performance, making the model reliable for breast cancer diagnosis.

🧾 Detailed Interpretation
1️⃣ Precision

Precision tells us how many predicted positive cases were actually correct.

Class 0 (Malignant): 0.98

Class 1 (Benign): 0.97

This means the model produces very few false positives.
It rarely predicts cancer when it's not present — which is extremely important in medical diagnosis.

2️⃣ Recall

Recall measures how many actual positive cases the model successfully identifies.

Class 0 (Malignant): 0.95

Class 1 (Benign): 0.99

A recall of 0.99 for benign tumors indicates the model almost never misses non-cancerous cases.
The slightly lower recall for malignant tumors (0.95) still indicates strong detection ability.

3️⃣ F1-Score

The F1-score balances precision and recall.

Class 0 (Malignant): 0.96

Class 1 (Benign): 0.98

Both classes show high F1-scores, confirming that the model is balanced and performs consistently across categories.

🟦 Confusion Matrix Interpretation

Your confusion matrix:

	Predicted 0	Predicted 1
Actual 0	41	2
Actual 1	1	70
Key observations:

41 malignant tumors correctly identified

70 benign tumors correctly identified

Only 3 misclassifications out of 114 samples

This explains the high accuracy score and shows the model rarely makes mistakes.
