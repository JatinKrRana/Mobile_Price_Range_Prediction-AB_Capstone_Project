# Mobile_Price_Range_Prediction-AB_Capstone_Project

![download](https://github.com/user-attachments/assets/f0dc1a4b-cf43-4cb9-8d45-81439890810b)

In the fast-evolving landscape of technology, predicting the price range of mobile phones has become a critical task for both consumers and manufacturers. In this Mobile Price Range Prediction project, we delve into the realm of Machine Learning Classification to develop a model that can accurately predict the price range of mobile devices based on various features. The project involves several stages, including exploratory data analysis (EDA),data preprocessing, and the implementation of supervised machine learning algorithms such as Logistic Regression, Random Forest Classifier, and XG Boost Classifier.

## Exploratory Data Analysis (EDA):
Our journey commences with a detailed exploration of the dataset through EDA. Visualization tools and statistical techniques are employed to uncover patterns, trends, and relationships within the data. Descriptive statistics provide a snapshot of central tendencies, while data distribution plots illuminate the spread of key variables. Correlation matrices help discern connections between different features.

![download (1)](https://github.com/user-attachments/assets/d85fde3b-5c17-4def-9140-01461ade7a8e)
![download (5)](https://github.com/user-attachments/assets/80160e7f-08f0-4def-8de7-aeb355d49954)
![download (6)](https://github.com/user-attachments/assets/789c9be4-9a18-4897-a51f-c313a24616c1)
![download (2)](https://github.com/user-attachments/assets/005b9a8f-2814-495c-9b82-967b3db211b8)
![download (3)](https://github.com/user-attachments/assets/12108efa-7a0a-41c2-bb03-aad949e91bd5)
![download (7)](https://github.com/user-attachments/assets/d6001a45-c7b0-47ce-8cc5-c3c0f63c5876)
![download (4)](https://github.com/user-attachments/assets/05da6695-9dcf-4aaf-90a6-bcb6faa80c31)


## Data Preprocessing:
Building on the insights from EDA, we transition to the essential phase of data preprocessing. Obtaining a relevant and comprehensive dataset is fundamental to the success of any machine learning endeavor. This dataset, containing information about various mobile phones and their features, forms the foundation for our predictive model.
1. Feature Selection
![Screenshot 2024-09-01 233742](https://github.com/user-attachments/assets/a6e6ceb8-04d9-4d30-bf13-4e3145a96774)

2. Data Transformation
![Screenshot 2024-09-01 233931](https://github.com/user-attachments/assets/d2155503-a451-461e-af7b-ecbc435cc23c)

3. Data Scaling
![Screenshot 2024-09-01 234102](https://github.com/user-attachments/assets/f4f326dd-d7dd-4f79-9be9-cf995d1c9d3a)

4. Data Splitting
![Screenshot 2024-09-01 234211](https://github.com/user-attachments/assets/27b4115a-d119-4a9e-8953-0c3414b38e6b)

5. Handling Imbalanced Dataset
![Screenshot 2024-09-01 234522](https://github.com/user-attachments/assets/a710b788-f639-49c2-8336-685b6cb3cce2)


## Supervised Machine Learning Algorithms and Implementation:
The heart of the project lies in the implementation of supervised machine learning algorithms. Three powerful classifiers—Logistic Regression, Random Forest Classifier, and XG Boost Classifier—are chosen for their effectiveness in classification tasks.

### Logistic Regression: 
Logistic Regression is a linear model used for binary classification. In our project, it serves as a baseline model, providing a simple yet effective approach to predict mobile price ranges. The algorithm calculates the probability of a mobile belonging to a particular price range based on its features.

### Random Forest Classifier: 
Random Forest is an ensemble learning algorithm known for its robustness and high accuracy. It operates by constructing multiple decision trees during training and outputs the mode of the classes as the prediction. Random Forest is particularly effective in handling complex relationships within the data.

### XG Boost Classifier: 
XG Boost, or Extreme Gradient Boosting, is a powerful and efficient algorithm that belongs to the gradient boosting family. It sequentially builds a series of weak learners to create a strong predictive model. XG Boost is known for its speed and performance, making it a popular choice in machine learning competitions.

![Screenshot 2024-09-01 234645](https://github.com/user-attachments/assets/c4dc6e5b-b361-43b0-bc97-1f2b0229a41d)

Logistic Regression with GridSearchCV (cross-validated hyperparameter tuning) demonstrates the highest precision, recall, F1 Score, and roc_auc_score among the models. This suggests that the Logistic Regression model with optimized hyperparameters may be a suitable choice for the final prediction model, providing a good balance between precision, recall, and overall classification performance.

In conclusion, the Mobile Price Range Prediction project combines data preprocessing, exploratory data analysis, and the implementation of three supervised machine learning algorithms to create a robust predictive model. The outcome of this project not only provides valuable insights into the factors influencing mobile prices but also showcases the power of machine learning in solving real-world problems in the technology domain.
