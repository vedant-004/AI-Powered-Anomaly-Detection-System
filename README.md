# AI-Powered-Anomaly-Detection-System
This project implements an anomaly detection system for transaction data using machine learning techniques. The aim is to identify unusual transactions that may indicate fraudulent activity or errors.

    Dataset
The dataset used in this project includes the following columns:

Transaction_ID: Unique identifier for each transaction.

Transaction_Amount: Amount of the transaction.

Transaction_Volume: Volume or frequency of transactions.

Average_Transaction_Amount: Average amount of transactions for the account.

Frequency_of_Transactions: Number of transactions over a specified period.

Time_Since_Last_Transaction: Time elapsed since the last transaction.

Day_of_Week: Day of the week the transaction occurred.

Time_of_Day: Time of day the transaction occurred.

Age: Age of the account holder.

Gender: Gender of the account holder.

Income: Income of the account holder.

Account_Type: Type of the account (e.g., savings, checking).

Usage
The project provides several functionalities:

Data Visualization:
Generates visualizations for transaction amounts, distributions, and correlations.

Anomaly Detection:
Identifies anomalies in transaction amounts using statistical methods and the Isolation Forest model.

User Interaction:
Allows users to input transaction details and check for anomalies.

To interact with the project, run the main script and follow the prompts to input transaction details for anomaly detection.
