# Food Delivery Time Prediction

This project predicts food delivery time based on various factors like distance, weather, and traffic conditions. The analysis is done using a Jupyter Notebook and includes data preprocessing, model training, and evaluation.

## Datasets

This project uses the `Food_Delivery_Time_Prediction.csv` dataset, which includes the following columns:

* `Order_ID`
* `Customer_Location`
* `Restaurant_Location`
* `Distance`
* `Weather_Conditions`
* `Traffic_Conditions`
* `Delivery_Person_Experience`
* `Order_Priority`
* `Order_Time`
* `Vehicle_Type`
* `Restaurant_Rating`
* `Customer_Rating`
* `Delivery_Time`
* `Order_Cost`
* `Tip_Amount`

### Prerequisites

You need to have Python and Jupyter Notebook installed. You can install the required libraries using pip:
pip install -r requirements.txt

## How to run
1.Clone the repo:
git clone [https://github.com/your_username/your_repository_name.git](https://github.com/your_username/your_repository_name.git)

2.Navigate to the project directory:
cd your_repository_name

3.Open the Jupyter Notebook:
jupyter notebook food_deilveryPART2.ipynb

## Models
The following models were used for prediction:

Gaussian Naive Bayes

K-Nearest Neighbors (KNN)

Decision Tree Classifier

## Results
The models were evaluated based on accuracy, precision, recall, and F1-score. The K-Nearest Neighbors model with the best K value performed the best.
