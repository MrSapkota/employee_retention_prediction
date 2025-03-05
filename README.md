# Employee_retention_prediction
Employee Retention Prediction 🚀

A machine learning project that predicts employee retention using various classification algorithms.

* Overview
This project analyzes employee data to predict whether an employee is likely to stay or leave a company. The dataset contains various features like city, education level, experience, company size, and more. We apply different machine learning models to evaluate and compare their performance.

* Dataset
The project uses two datasets:

  -aug_train.csv: Training dataset

  -aug_test.csv: Testing dataset


* Key Steps in the Project


* ✔ Data Preprocessing
  -Handling missing values
  
  -Encoding categorical features
  
  -Normalization & standardization


* ✔ Exploratory Data Analysis (EDA)

  -Understanding numerical and categorical feature distributions
  
  -Detecting potential biases and outliers
  
  -Visualizing trends using histograms, box plots, and bar charts


* ✔ Feature Engineering

  -One-hot encoding categorical features
  
  -Selecting relevant features for training

* ✔ Model Training & Evaluation

  -Logistic Regression
  
  -Random Forest Classifier
  
  -K-Nearest Neighbors
  
  -Evaluated using Accuracy & F1-Score

* ✔ Results & Insights

    -Identified key factors influencing employee retention
  
    -Compared model performances using accuracy and F1-score




![image](https://github.com/user-attachments/assets/70b52ab3-d898-4045-a61d-96f71dda7da9)

![image](https://github.com/user-attachments/assets/3a93a908-5ae5-4620-ae61-2520ebb71632)

![image](https://github.com/user-attachments/assets/5759bc93-a6e4-4650-8d0a-88dd5443a8fe)

![image](https://github.com/user-attachments/assets/0950e156-bcee-402a-8cee-ec1fa1b23024)

![image](https://github.com/user-attachments/assets/79c10b25-5ec7-4ef4-be06-505f9ac2d7e5)

![image](https://github.com/user-attachments/assets/4a0673ec-4fdd-425b-b40e-ec7e6f45dbaf)


![image](https://github.com/user-attachments/assets/f06f0e64-c4a7-4feb-887c-250637b73fdf)

* This code segment helps us to understand the categorical data within the datasets by identifying the different categories (unique values) and how often they occur (value counts) for each categorical column in both the training and test datasets.


![image](https://github.com/user-attachments/assets/0d102268-7700-4221-85dd-e997159d6380)

*The code selects the numerical columns (city_development_index, training_hours) from both df_test and df_train DataFrames. It then uses the .describe() method to calculate and display descriptive statistics (like mean, standard deviation, min, max, percentiles) for these columns in both datasets, enabling easy comparison of their numerical characteristics.


![image](https://github.com/user-attachments/assets/a4981ed6-d9cc-478c-b7b4-5d86f45e0fb8)


![image](https://github.com/user-attachments/assets/35c946d6-16a9-4179-ae6d-7ed15c196249)


![image](https://github.com/user-attachments/assets/ce127517-c957-46b6-8653-8a483cc77997)


![image](https://github.com/user-attachments/assets/b04acf2a-eef0-4b4f-b118-c9ea637bc769)


![image](https://github.com/user-attachments/assets/fc456da2-fe38-4e13-a228-9a47c2be3391)



![image](https://github.com/user-attachments/assets/a0e84a62-d929-4434-b09c-cc37a973b07a)


![image](https://github.com/user-attachments/assets/845adf54-f83b-47f1-a95f-7ff77e235ccb)

*city_development_index: The histograms would reveal the distribution of city development indices in both the training and test sets.

*Skewness: Whether the distribution is skewed (leaning more towards lower or higher values).

*Modality: Whether there are multiple peaks in the distribution, suggesting distinct groups of cities with different development levels.

*Differences between Train and Test: the distributions in the training and test sets are similar or significantly different, which could impact model performance.



*training_hours: The box plots would provide information about:

*Central Tendency: The median (represented by the line inside the box) of training hours.

*Spread/Dispersion: The interquartile range (IQR), represented by the box's height, shows the spread of the middle 50% of the data.

*Outliers: Points outside the whiskers of the box plot are potential outliers, indicating unusually high or low training hours.

*Differences between Train and Test: comparing the medians, IQRs, and outlier patterns between the training and test sets to see if there are significant differences.


![image](https://github.com/user-attachments/assets/bec76527-b441-4005-9f5a-53e263733384)


![image](https://github.com/user-attachments/assets/8f6716ff-97eb-4e07-82b6-1ee037c35623)


![image](https://github.com/user-attachments/assets/ccc2f2a1-71a6-4e24-92ea-310335f6e263)

* Gender: If the count plot for 'gender' shows a significant difference between the number of males and females, it could indicate a potential bias in the dataset.

* Relevant Experience: The count plot for 'relevent_experience' can reveal the proportion of candidates with prior experience, which might be a crucial factor for predicting their job-seeking behavior.

* Education Level: The distribution of education levels can offer insights into the qualifications of candidates in the dataset.

* Company Size: The count plot for 'company_size' can highlight the prevalence of different company sizes, which might be relevant for understanding job market trends.


![image](https://github.com/user-attachments/assets/84baac63-f187-4717-9e38-bdae27617508)

* the target variable plot provides crucial information about the distribution of the target variable and helps identify the presence of class imbalance, which is a critical factor to consider when building a classification model. By carefully examining this plot, we can make informed decisions about addressing class imbalance and improving the performance of our model.


![image](https://github.com/user-attachments/assets/353d6d46-a305-42e3-a919-801c56524536)


![image](https://github.com/user-attachments/assets/71e0a3c4-a2be-46e8-a272-1a1a7af4296c)


![image](https://github.com/user-attachments/assets/5263514f-05a5-4ac1-a66d-e30a7b237b18)


![image](https://github.com/user-attachments/assets/19c87de5-cd01-4f07-a8ab-b26779077757)


![image](https://github.com/user-attachments/assets/03efa67a-4b2d-49c6-a23a-d2c622487203)


![image](https://github.com/user-attachments/assets/2b5faeaf-f6a5-40e1-9fdf-0a6daf540228)


![image](https://github.com/user-attachments/assets/693bf091-907c-400f-a62d-b9cc872dfc08)



![image](https://github.com/user-attachments/assets/22fc3fc7-8b50-4d16-8ed0-079ab59754f8)


![image](https://github.com/user-attachments/assets/cef36b86-d6db-4772-aedf-875170207b8d)


![image](https://github.com/user-attachments/assets/a56a3ebf-55eb-4ea7-b3dd-b0ef00ec0855)


![image](https://github.com/user-attachments/assets/e3e46369-35ca-47f6-94aa-0644c26a3d1a)


![image](https://github.com/user-attachments/assets/0624a58a-5a62-4d8d-aff7-30f0cdf47b93)


![image](https://github.com/user-attachments/assets/62c0bf05-5ff0-46d7-927a-d9000eb59a3e)


















