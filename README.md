# ETL
A project where I was assigned to create an ETL pipeline and perform visualization on it using PowerBI
1. Data Loading and Exploration:
   - The code loads a CSV file containing car prediction data using pandas.
   - It prints the column names and the first few rows of the dataset to understand its structure.

2. Data Preprocessing:
   - Drops missing values from the dataset.
   - Selects specific columns for analysis while excluding the specific columns.
   - Performs one-hot encoding on categorical columns.
   - Creates a new feature based on the column and performs one-hot encoding on it.
   - Drops the columns after creating the new features.
   - Drops any remaining missing values.
3. Data Splitting and Model Training:
   - Splits the dataset into training and testing sets.
   - Initializes a Random Forest Regressor model.
   - Trains the model using the training data.

4. Model Evaluation:
   - Makes predictions on the test set using the trained model.
   - Computes the Mean Squared Error (MSE) between the predicted and actual values.
   - Prints the MSE to evaluate the model's performance.

5. Summary Statistics:
   - Calculates summary statistics for the encoded dataset using the `describe()` function.

6. Saving the Modified Dataset:
   - Saves the modified DataFrame back to a new CSV file named 'modified_data.csv
  
7. Interactive Dashboards:
   - Power BI enables the creation of interactive dashboards where all these visualizations and summaries can be brought together. Users can filter, drill down, or interact with the data dynamically, offering a          comprehensive understanding of the dataset and model predictions.
Power BI facilitates the creation of rich, interactive visualizations and reports that allow for comprehensive data exploration, model evaluation, and presentation of summary statistics. It helps in communicating insights effectively to stakeholders by presenting data in a visually compelling and understandable format.



