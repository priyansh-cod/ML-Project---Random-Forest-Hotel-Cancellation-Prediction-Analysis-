# _Hotel Booking Cancellation Prediction using Python _ 🏨
This project utilizes the Hotel_Booking dataset to predict the likelihood of booking cancellations. The dataset includes features such as hotel type, meal plan, country, deposit type, number of adults and children, and more. By analyzing this data and building a predictive model, we aim to provide insights into factors influencing cancellations, helping hotels manage reservations more effectively.

# Project Structure :
*1 Data Exploration & Pre-processing To ensure data quality and model accuracy.*

- *Dataset Loading:* Load and inspect the dataset.<br>
- *Unique Value Analysis:* Print unique values in all columns for an overview of each feature.<br>
- *Data Imputation*:
  - Fill NaN values with "other" for categorical columns.<br>
  - Replace missing values in the agent column with its mean value.<br>
- *Null Value Handling:* Drop any remaining rows with null values.<br>
- *Data Visualization:* Plot a bar chart to show counts of adults and children to visualize booking demographics.<br>
- *Encoding Categorical Variables:* Use label encoding to transform categorical columns for model compatibility.<br>

*2: Model Building To predict cancellation probability.*

- *Define Features and Target:* Prepare the dataset by selecting features and target variables.<br>
- *Data Splitting:* Divide data into training and testing sets.<br>
- *Random Forest Classifier:* Apply the Random Forest algorithm to make predictions.<br>
- *Evaluation Function:* Create a function to display model metrics including Precision, Recall, Accuracy, Classification Report, and Confusion Matrix.<br>

# Technologies Used 👨‍💻
- *Python:* Data processing and modeling.<br>
- *Pandas & NumPy:* Data manipulation and handling.<br>
- *Matplotlib & Seaborn:* Data visualization.<br>
- *Scikit-learn:* Machine learning model building and evaluation.<br>

# Evaluation Metrics 💹
*To assess model performance.<br>*

- *Precision*<br>
- *Recall*<br>
- *Accuracy Scores*<br>
- *Classification Report:* Summarizes key metrics per class.<br>
- *Confusion Matrix:* Visualizes true vs. predicted values.<br>
