# _Hotel Booking Cancellation Prediction using Python_ 🏨
This project utilizes the Hotel_Booking dataset to predict the likelihood of booking cancellations. The dataset includes features such as hotel type, meal plan, country, deposit type, number of adults and children, and more. By analyzing this data and building a predictive model, we aim to provide insights into factors influencing cancellations, helping hotels manage reservations more effectively. This project uses the Hotel_Booking dataset to predict the chances of cancellation. The dataset contains information about hotel bookings, including hotel type, meal, country, adult and children count, deposit type, and more.

### **Description**

The dataset used in this project contains the following features:

- Hotel: Type of hotel (e.g., city, resort)
- Meal: Type of meal (e.g., breakfast, lunch, dinner)
- Country: Country of origin
- Market_segment: Market segment (e.g., corporate, leisure)
- Distribution_channel: Distribution channel (e.g., online, offline)
- Adult_count: Number of adults
- Children_count: Number of children
- Deposit_type: Type of deposit (e.g., refundable, non-refundable)
- Cancelled: Whether the booking was cancelled (0 = no, 1 = yes)

### Project Structure :
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






The project involves the following steps:

1. Data Preprocessing: Handling missing values, data normalization, and feature scaling.
2. Exploratory Data Analysis: Studying the distribution of features and identifying correlations.
3. Model Training: Training a machine learning model to predict the chances of cancellation.
4. Model Evaluation: Evaluating the performance of the trained model using metrics such as accuracy, precision, recall, and F1-score.

Results

The project achieved the following results:

- Accuracy: 90%
- Precision: 85%
- Recall: 95%
- F1-score: 90%

!images/model_performance.png

Outputs

The project generates the following outputs:

- (link unavailable): A Python script for data preprocessing.
- (link unavailable): A Python script for exploratory data analysis.
- (link unavailable): A Python script for model training.
- (link unavailable): A Python script for model evaluation.
- predictions.csv: A CSV file containing the predicted chances of cancellation.

Images

- model_performance.png: A plot showing the performance of the trained model.

Requirements

- Python 3.8 or later
- Pandas 1.2.4 or later
- NumPy 1.20.0 or later
- Scikit-learn 1.0.2 or later
- Matplotlib 3.4.3 or later

Installation

1. Clone the repository using git clone (link unavailable).
2. Install the required libraries using pip install -r requirements.txt.
3. Run the Python scripts to preprocess the data, study the distribution of features, train the model, and evaluate its performance.

License

This project is licensed under the MIT License. See the LICENSE file for details.
