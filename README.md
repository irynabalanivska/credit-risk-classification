# credit-risk-classification
module 20
GPT
Objective
The objective is to evaluate the effects of oversampling on the performance of two logistic regression models: one trained using the original dataset and another using the oversampled dataset, focusing on their ability to predict high-risk loans.

Observations

High-Risk Loan Prediction (Label 1)

Precision: Remained constant at 0.84 in both models, indicating no change in the accuracy of high-risk loan predictions relative to the positive predictions made by the models.
Recall: Improved from 0.94 to 0.99, highlighting a notable enhancement in the model’s ability to identify high-risk loans, which suggests that oversampling has effectively aided the model in better understanding the characteristics of high-risk loans.
F1-Score: Increased from 0.89 to 0.91, reflecting an improvement in the model’s overall precision and recall balance for high-risk loan predictions.
Healthy Loan Prediction (Label 0)

Precision, Recall, and F1-Score: These metrics remained very high (precision at 1.00 and recall at 0.99) with the F1-score consistently at 1.00, demonstrating that the model’s performance in correctly identifying healthy loans was already excellent and maintained even after the oversampling intervention.
Overall Model Performance

Accuracy: Stayed consistent at 0.99 for both models, showing that the overall accuracy of the models in making correct predictions did not vary significantly.
Macro Avg: The macro average for recall increased from 0.97 to 0.99, indicating an improvement in the model’s ability to correctly recognize both classes. The macro average F1-score also rose from 0.94 to 0.95, suggesting a slight enhancement in achieving a balance between precision and recall across classes.
Weighted Avg: Remained steady with precision, recall, and F1-scores all at 0.99, confirming that the model’s performance across different classes stayed uniform.
Summary
The primary improvement with the logistic regression model trained on the oversampled data is observed in the recall for high-risk loans (label 1), which shows enhanced capability in nearly identifying all high-risk loans. This enhancement is crucial, particularly in scenarios where missing a high-risk loan could lead to significant repercussions, even though the precision remained unchanged. The model's consistent ability to recognize healthy loans shows that oversampling the minority class did not adversely impact the performance on the majority class, maintaining crucial balance and reliability of the model in practical applications.
