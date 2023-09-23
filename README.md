# Bank-Marketing-Campaign
This GitHub repository contains code for predicting whether customers will subscribe to a bank's term deposit based on marketing campaign data. This can help the bank target potential customers more effectively.

**Overview**
The project uses machine learning on historical customer data to make predictions. Here's a simplified structure of the repository:
Data: The dataset is already in this repository named data_bank_marketing_campaign.csv.
Notebooks: The code is in Jupyter Notebook named Vincent_MachineLearning_BankMarketingCampaignClassification.ipynb in this repository.
Models: The final model used is saved in a file named Vincent_FinalModel_BeforeThreshold.sav in this repository.
The final model saved is the one that performs the best after hyperparameter tuning. However, it's important to note that the best results can only be achieved after optimizing its threshold, which is set to 0.483077. Therefore, before using the model for predictions, remember to set its threshold to 0.483077.

## Code Flow
1. **Domain Knowledge**: Understand related domain knowledge.
2. **Business Problem**: Define the problem.
3. **Data Understanding**: Explore the dataset, understand its features and target.
4. **EDA**: Discover insights and patterns in the data.
5. **Data Preprocessing**: Clean and prepare the data.
6. **Define Target and Features**: Identify what to predict and input variables.
7. **Data Splitting**: Split the data for training and testing.
8. **EDA for Classification**: Analyze data specific to classification.
9. **Classification Metrics**: Determine measure model performance.
10. **Cross Validation**: Check model's generalization.
11. **Hyperparameter Tuning**: Optimize model settings.
12. **Predictions (Before & After Tuning)**: Evaluate model results.
13. **Optimize Threshold**: Fine-tune threshold for better recall.
14. **Feature Importance**: Identify influential features.
15. **Conclusion**: Summarize findings.
16. **Recommendation**: Suggest strategies for the bank.
