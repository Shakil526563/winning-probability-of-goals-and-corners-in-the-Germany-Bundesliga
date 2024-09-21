Here’s a summary of everything I’ve explored and learned in this process:

1. Feature Selection and Engineering
You worked with football match data and selected relevant features such as goals, shots on goal, fouls, blocked shots, yellow cards, and more to predict high corner kicks.
Created a new target variable (high_corners) based on corner kicks, labeling games with more than 5 corner kicks as high.
2. Data Preprocessing
Handling Missing Data: Utilized SimpleImputer to fill in missing values using the mean strategy, ensuring a complete dataset for modeling.
Feature Scaling: Applied StandardScaler to standardize the feature set, allowing models like Logistic Regression to perform better by normalizing the ranges of all the variables.
3. Train-Test Split
Split the dataset into training and testing sets using train_test_split, ensuring that 80% of the data was used for training and 20% for evaluation.
4. Modeling with Logistic Regression
Trained a Logistic Regression model with all features and then refined it by focusing on the top 18 most important features.
Extracted coefficients from the Logistic Regression model to identify the most influential features in predicting the target variable (high_corners).
5. Feature Importance and Visualization
Ranked the features by their importance in the Logistic Regression model based on the absolute values of their coefficients.
Visualized the feature importance using a bar plot to easily interpret the model’s focus on key features.
6. Model Evaluation
Accuracy Calculation: Calculated the model’s accuracy on the test set, showing the effectiveness of Logistic Regression with selected features.
Confusion Matrix: Generated a confusion matrix to understand the performance of the model in terms of true positives, false positives, true negatives, and false negatives.
Classification Report: Produced detailed classification metrics (precision, recall, F1-score) to provide deeper insights into how well the model classified low and high corner scenarios.
7. Visualization Techniques
Used seaborn to create a heatmap visualizing the confusion matrix, making the classification performance easier to interpret.
Bar plots were employed to represent the feature importances, with proper labeling and formatting for clear communication of the results.


![download (1)](https://github.com/user-attachments/assets/084e1acf-4493-4adb-98fc-955a323e0930)
![download (2)](https://github.com/user-attachments/assets/8519bd89-05e3-4c5a-98f5-c14e5c3c7265)
![download (3)](https://github.com/user-attachments/assets/09cf0b81-38e4-474d-8c49-e601e855d9ea)
![download (4)](https://github.com/user-attachments/assets/91b7f875-cc7e-43c4-9168-3035e4a08322)
![download (5)](https://github.com/user-attachments/assets/afbc124e-f447-453d-ac97-f43cabe10fd8)
![download (6)](https://github.com/user-attachments/assets/ffc5855b-3b14-4536-92f8-09c4e01278f1)
![download (7)](https://github.com/user-attachments/assets/be40791f-a3b6-4cb2-a470-e4d653a7e6da)
![download (8)](https://github.com/user-attachments/assets/19a6e457-796b-4d10-bc5c-c2c67339271a)
![download](https://github.com/user-attachments/assets/3883dc06-3a9f-4235-adce-fdbb6e54d336)




