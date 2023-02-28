In this repo I approach the problem credit card fraud detection, I treat it as a binary classification problem. However, the nature of credit card fraud detection makes it challenging to build an optimal decision boundary due to the heavily imbalanced distribution of the data. To tackle this challenge, I follow a step-by- step approach.Firstly, I explore the distribution of data variables with respect to fraud and non- fraud transactions to gain insights into the data. Secondly, I use a simple statistical model such as logistic regression to understand the influence of different variables on fraud transactions.Next, I expand the model to a more flexible one, employing feature selection techniques and under-sampling the majority class to improve the model’s ability to predict fraud. I also demonstrate how boosting models like Lightgbm can be used to enhance model performance. In addition, I employ the use of Shapley values to explain the model predictions, which yields actionable insights for the business.

Finally, I conclude with a discussion of the findings and actionable insights. The notebook comprises the following steps:

• Data Exploration. • Modeling.
• Statistical Analysis.
– Logistic Regression.
∗ Feature Selection. - Recursive Feature Elimination. ∗ Under Sampling the Majority Class.
• Complex Model.
• Explainable AI.
• Conclusion, Discussion and Actionable Insights.