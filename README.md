# Cloud-based-Big-Data-Systems-Project

Use a major Big Data system to perform a Data Engineering related task <br>

Example systems could be: (AWS Athena, AWS Spark/EMR, AWS Sagemaker, Databricks, Snowflake) <br>

### PROCESS
#### week1:
- Build and configure labeling data job in AWS Sagemaker
- Review the labeling result
Note: dataset from Open dataset[Caltech 101]: https://data.caltech.edu/records/mzrjq-6wc02

#### week2:
This week, I confirm the data engineering project's main goal and implement it: I used a synthetically generated auto insurance claims dataset. The inputs are the training, validation, and test datasets, each containing details and extracted features about claims and customers along with a fraud column indicating whether a claim was fraudulent or otherwise. I used the open source XGBoost framework to build a binary classification model on this synthetic dataset to predict the likelihood of a claim being fraudulent. I also evaluated the trained model by running bias and feature importance reports, deployed the model for testing, and run sample inference to evaluate model performance and explain predictions. <br>

- Build, train, and tune a model using script mode
- Detect bias in ML models and understand model predictions
- Deploy the trained model to a real-time inference endpoint for testing
- Evaluate the model by generating sample predictions and understanding feature impact

#### DEMO:

https://user-images.githubusercontent.com/123136573/226252547-99b431a9-41dc-4319-a3e7-453388de70c9.mp4

