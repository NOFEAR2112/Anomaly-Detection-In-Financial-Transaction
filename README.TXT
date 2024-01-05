OVERVIEW
This Python script utilizes the pandas library to load and manipulate a dataset containing transaction information from a file named 'Final Transactions.csv'. It then employs the scikit-learn library to implement a Logistic Regression model for fraud detection. The model is trained on a subset of the data and evaluated for accuracy. Additionally, a user can make predictions by providing input features for a new transaction.

DEPENDENCIES
pandas
numpy
scikit-learn (sklearn)
Make sure to install these dependencies before running the script. You can install them using the following:

USAGE
Ensure you have the required dataset ('Final Transactions.csv') in the same directory as the script.
Execute the script in a Python environment.

CODE STRUCTURE
Import Statements: Import necessary libraries (pandas, numpy, sklearn).
Load and Explore Data: Read the CSV file into a Pandas DataFrame, explore the dataset, and preprocess the 'TX_DATETIME' column to extract the year.
Data Splitting: Split the data into features (x) and the target variable (y), and further split them into training and testing sets using the train_test_split function.
Logistic Regression Model: Create a Logistic Regression model using LogisticRegression from scikit-learn and train it on the training data.
Model Evaluation: Evaluate the accuracy of the model on both the training and testing sets using the accuracy_score function.
User Prediction: Demonstrate how to make predictions for a user-provided transaction using the trained model.
Execution
To run the script, execute it in a Python environment. The results will include the accuracy of the model on the training and testing sets, as well as a prediction for a user-provided transaction.

NOTE
The script assumes that the dataset contains columns named 'TX_DATETIME', 'TX_FRAUD', 'TX_FRAUD_SCENARIO', and other relevant features. Ensure your dataset adheres to this structure.
The model's performance on new data may vary, and additional model evaluation metrics could be considered for a more comprehensive assessment.
Feel free to customize the code to fit your specific use case or extend it for further analysis.




